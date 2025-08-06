this playbook ping the whole subnet that you gave it from remote servers in inventory file under <check_servers> group.

how to run:

ansible-playbook -i inventory.ini configure_and_check.yml --extra-vars "subnet_input=94.182.128.64/28"
