# Jboss Installation on Ubuntu 14.04 using Ansible
--------
This playbook deploys Jboss Server on Ubuntu 14.04 LTS.


## Then run this playbook:

```
ansible-playbook jboss.yml --extra-vars "hosts=192.168.1.78 user=harpreet group=root"
```
**Note:** Change below details in above ansible command. 
```
hosts # ip address on which to install jboss
user  # user to be used for istallation
group  # group to be used for installation 
```
To Check Jboss installtion open http://localhost:8080

