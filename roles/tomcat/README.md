# Tomcat Installation on Ubuntu 14.04 using Ansible
--------
This playbook deploys Tomcat Server on Ubuntu 14.04 LTS.


## Then run this playbook:

```
ansible-playbook tomcat.yml --extra-vars "hosts=192.168.1.78 user=harpreet group=root admin_username=admin admin_password=adminsecret"
```
**Note:** Change below details in above ansible command. 
```
hosts # ip address on which to install tomcat
user  # user to be used for istallation
group  # group to be used for installation 
admin_username # tomcat gui manager username 
admin_password # tomacat gui manager password 
```
To Check Tomcat installtion open http://localhost:8080

