# ansible
To use the play book, user ansible-playbook command. If the name of inventory file being used is not "hosts", 
then add the -i (inventory) option to let ansible knows to look for other inventory file's name

```
ansible-playbook -i /etc/ansible/myhosts /etc/ansible/backup_cisco.yaml
```
