# wordpress_deployment_Ansible
wordpress deployment on host machine using ansible playbook from https://github.com/diranetafen/ansible-role-containerized-wordpress/tree/master .

To use it you first have to deploy an ansible machine with a host. 

firs install playbook from link given earlier : 
ansible-galaxy install -r roles/requirements.yml

run with command : ansible-playbook -i hosts.yml --ask-vault-password wordpress.yml
