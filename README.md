# Altschool-Secondsemesterexam
Vagrant up --> To create the Virtual machines

Vagrant ssh master --> To access the master VM which is also the control/host machine for Ansible

Inside the master VM, run cd ansible to access the Ansible folder where the playbook and host inventory are stored

ansible all -i host-inventory -m ping to verify the connection between master and slave

ansible-playbook playbook.yml -i host-inventory --> To run the playbook and provision the LAMP stack on the slave machine
