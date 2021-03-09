To run the playbook:
1. setup the server with ssh access where grafana is to be installed.
2. change IP in inventory/hosts file.
3. run below command
ansible-playbook -i inventory/ play.yml