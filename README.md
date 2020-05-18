Install / ocnfigure gluster on C7

# Setup the VM

```
vagrant up
```

# Launch ansible

```
ansible-galaxy install geerlingguy.glusterfs
ansible-playbook -i inventories/test playbook.yml
```
