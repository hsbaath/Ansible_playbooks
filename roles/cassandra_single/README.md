# Cassandra Installation on Ubuntu 14.04 using Ansible
--------
This playbook deploys NoSQL database Cassandra on Ubuntu 14.04 LTS.


## Then run this playbook:

```
ansible-playbook cassandra.yml --extra-vars "hosts=192.168.1.78 user=harpreet group=root"
```

**Note:** Change Variables `hosts` , `user` and `group` with user details. 


