# Ansible Pull Example

### Syntax for ansible-pull

```
ansible-pull -o -C master -d /root/ansible -U git@github.com:kwongshomi/ansible-pull-test.git --accept-host-key -i localhost,
```

This checks out the master repo into "/root/ansible" using the clone URL specified by "-U".
The "-i" tells ansible to use the localhost as it's host inventory (ie. run on itself)
