## Deploy vagrant  

- - - -  
#### Version dependency  
1. Ansible: `2.5.1`
2. Python:  `3.6.5`


- - - -  
#### Role dependency  
```
None
```


- - - -  
#### VARS
```
None
```


- - - -  
#### Playbook example  


```yml
---
- hosts: slaves
  become: yes

  roles:
    - ansible-role-file-replication
```
