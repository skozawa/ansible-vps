Ansible files for VPS

http://comainu.org/

## local
```
vagrant up
ansible-playbook -i hosts playbook.yml
```

access http://localhost:3000/

## production
```
ansible-playbook -i hosts playbook.yml --ask-sudo-pass
```
