This example covers overriding the default ansible.cfg file to custom needs

Setting up the custom configuration for other than ansible configuration
Ansible uses the shell variable ANSIBLE_CONFIG=/home/whatever/path/you/want

ie: export ANSIBLE_CONFIG=/home/ansible/path/config/ansible.cfg

# Order of Precedent for searching the config file
	/etc/ansible/ansible.cfg
	/currentdirectory/where/the/config/file/is
	/home/test/.ansible.cfg
# This the path where Ansible check for order of precedent
	

