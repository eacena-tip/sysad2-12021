### How to create an Ansible Configuration  
1. Check first if you already install ansible in your OS by entering the command `ansible --version`.
2. If not enter the command `apk add ansible` in order to install ansible.
3. Create a configuration file in vim using the command `vim ansible.cfg`.
4. Go inside the ansible.cfg file and input the information needed.
5. Check the information inside it, it should contain information such as inventory, remote user, privilege escalation.
6. Save and quit the file using the command `wq`.
7. Check or view the information inside the file by `cat` command.


### How to create an Ansible Inventory
1. Check your ansible.cfg file if you already inserted the need information and look for inventory.
2. Make a file inventory with the same name from the ansible.cfg. 
3. Insert the needed information such as hosts and ip addresses.
4. Save and quit using `wq` command.  


### How to create an Ad-hoc Ansible command with setup and shell module
1. For setup module you can use the command `ansible <hostname> -m steup` to gather information about your system.
2. In shell module use the command `ansible -m shell -a` to run a linux command.
