# Cassandra multi node installation using anisble
-----
This playbook deploys NoSQL database Cassandramulti node on Ubuntu 14.04 LTS.

## To use this Playbook:

Edit the ansible `hosts inventory` file :
```
[node1]
192.168.1.78

[node2]
192.168.1.79
```
 Replace the `ip adress` of node1 and node2.


### To run this playbook:

```
ansible-playbook cassandra_multi.yml --extra-vars "ipnode1=192.168.1.78 ipnode2=192.168.1.79 remote_user=harpreet user=hsbaath group=root"
```

**Note:** Change below details in above ansible command. 
```
ipnode1 # cassandra node1 ip address
ipnode2  # cassandra node2 ip address
remote_user  # remote user used by ansible 
user # cassandra user 
group # cassandra user group 
```


