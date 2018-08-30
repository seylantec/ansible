# Subtitution command for installing custom packages with ansible command

first check weather the product is existing in the system
ansible local -s -m yum -a "name=bluefish state=absent"

ansible-playbooks variablessubtitution.yaml --extra-vars "hosts=local gather=yes pkg=bluefish" 


