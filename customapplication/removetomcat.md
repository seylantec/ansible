# removing the tomcat with ansible
ansible local -s -m yum -a 'name=tomcat state=absent'

