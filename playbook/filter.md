To Simple fileter in ansible use
#ansible host -m setup -a 'filter=*ipv4*'
This will return all the ipv4 sections form the setup module.
output to a file this will create a directory and files inside
#ansible host -m setup --tree facts

#using variables in playbooks 

 
