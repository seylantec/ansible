#Ways of filtering results in ansible

following commands are related to ansible architecture

ansible local -m setup -a 'filter=ansible_architecture'
ansible local -m setup -a 'filter=ansible_distribution'
ansible local -m setup -a 'filter=ansible_dist*'
ansible local -m setup | grep distribution
ansible local -m setup -a 'filter=ansible_distribution_version'
ansible local -m setup -a 'filter=ansible_domain'
ansible local -m setup -a 'filter=ansible_fqdn'
ansible local -m setup -a 'filter=ansible_interfaces'
ansible local -m setup -a 'filter=ansible_kernel'


