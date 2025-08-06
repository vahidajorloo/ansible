this playbook will ping all of the ip addresses that are in the ips.txt file from the remote server in inventory.ini file under <check_servers> group

how to run:

ansible-playbook -i inventory.ini ping_ips_from_file.yml
