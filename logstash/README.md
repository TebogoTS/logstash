# Ansible ELK Playbook
 
This playbook is for setting up version 7.x of the ELK Stack on a remote server. 

## Notes and requirements

 - The playbook was built and tested on Ubuntu 18.04 VMs, for ELK versions 7.x 
 - You will need Ansible installed and running
 - Playbook is currently configured to set up the ELK stack in [site.yml] file.
 
 ## Instructions
 
 1. Edit your Ansible hosts file ('/etc/ansible/hosts') and add an 'elkservers' entry for the server you wish to install ELK on. You can of course name the host any way you want, this is just an example. 
 2. Verify connectivity to the ELK server.
 3. Cd into the directory, and run:
 `ansible-playbook site.yml`
 

