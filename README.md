# PI servers ansible

pi@192.168.1.32
pi@192.168.1.22

ansible-playbook playbooks/docker_install.yml 
ansible-playbook playbooks/pi_torrents.yml
ansible-galaxy install -r requirements.yml
ansible-vault decrypt inventories/group_vars/pi_servers/pi_servers_vaulted.yml
ansible-vault encrypt inventories/group_vars/pi_servers/pi_servers_vaulted.yml
ansible-inventory --graph

digital ocean server connect ssh root@165.227.210.141
