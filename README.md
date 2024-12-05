1. You need add ansible folder in / direcory
2. Then write these command:
   ~ cd /ansible/roles
   ~ ansible-galaxy collection install ansible.posix
   ~ ansible-galaxy collection install community.docker
   ~ ansible-playbook -i inventory.ini playbook.yml

References that were used:
1.	https://serverastra.com/docs/Tutorials/Set-Up-and-Secure-SSH-on-CentOS%2C-Rocky%2C-and-AlmaLinux-7%2C-8%2C-and-9
2.	https://stackoverflow.com/questions/62405671/ansible-playbook-to-check-the-condition-of-selinux-status
3.	https://docs.ansible.com/ansible/latest/collections/ansible/posix/selinux_module.html
4.	https://docs.ansible.com/ansible/latest/collections/ansible/posix/firewalld_module.html
5.	https://www.redhat.com/en/blog/ansible-chrony-daemon
6.	https://docs.ansible.com/ansible/latest/collections/ansible/builtin/yum_repository_module.html
7.	https://docs.ansible.com/ansible/latest/collections/ansible/builtin/service_module.html
8.	https://docs.ansible.com/ansible/latest/collections/community/docker/docker_image_pull_module.html
9.	https://docs.ansible.com/ansible/latest/collections/community/docker/docker_volume_module.html
10.	https://docs.ansible.com/ansible/latest/collections/community/docker/docker_container_module.html
11.	https://dev.to/dpuig/creating-an-ansible-playbook-to-install-and-configure-nginx-for-hosting-static-websites-3n6j?ysclid=m49mvzhyq0330020077
