# Example Ansible project for installing DefectDojo using godojo



## Info

Installing DefectDojo using godojo and Nginx for revers proxy.



## Getting started

- Set your variable values in ansible-defectdojo/group_vars/dojo.yml
- Set your server address and ansible user in ansible-defectdojo/inventory/inventory.yaml



## Installing DefectDojo

```bash
cd ansible-defectdojo
ansible-playbook playbook.yaml
```



## After Install

1. Login
2. Change Admin Email to your own.
3. Change "Email from" address.
4. Change Time Zone.



## Refs

- **DefectDojo:** https://github.com/DefectDojo/django-DefectDojo
- **godojo:** https://github.com/DefectDojo/godojo
- **Nginx:** http://nginx.org/
- **Ansible:** https://www.ansible.com/
