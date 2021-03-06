# Ansible Project
- [Ansible Basic Commands](https://github.com/hugoledra/Help-and-Manuals/blob/master/Ansible%20Comandos%20Basicos.txt)
- [Ansible Documentation](https://docs.ansible.com/)
- [About Ansible](https://docs.ansible.com/ansible/latest/index.html)

#### Summary of this project
At the end of this project, we will have two virtual machines, one to provide the Wordpress service (application server) and another to provide the database service Mysql (database server).
- Remember to review and update the ansible_ssh_private_key_file in hosts file before running the Ansible.

#### Requirements to run this project
Ansible - Vagrant - Virtual Box

#### Run this project
```
$vagrant up
$ansible-playbook -i hosts provisioning.yml
```
Access the services in the urls file: [urls](https://github.com/hugoledra/Ansible-AluraCourse/blob/master/urls)

###### This project is based on the Alura course > [Ansible Course: Your Infrastructure as a Code](https://cursos.alura.com.br/course/infraestrutura-como-codigo-com-ansible)
