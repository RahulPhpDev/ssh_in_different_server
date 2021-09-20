# ssh_in_different_server


## in AWS

for an example aws_ssh
go to the folder where pem file is exist

### Ssh

```
ssh -i <pem_file_name> ubuntu@ip
```

now we get enter into sever

### next

```
 ssh -i <pem_file> ec2-user@<private_ip>
```
```
docker container ls
```

```
docker exec -it  <container_id> /bin/sh

```






## In window through putty 


### Visit C-panel 


### go to ssh form UI

click on  __generate key__

create a private -key

before download the key

__authorize__ the key

 download the key in local

now go to __putty__ 

**in Auth--> put this key path**


and put IP in Loggin

### How to get private key from AWS

Search for __Esc__ in aws

you will see different __cluster__ , select the cluster which need to do ssh

from __cluster__ select the Task [Screenshot_1]:https://github.com/RahulPhpDev/ssh_in_different_server/blob/main/ecs.png

from the __Task__ check for Private key here is [screenshot 2]:https://github.com/RahulPhpDev/ssh_in_different_server/blob/main/private.png

