Encripsion settings
The way to encrypt it with ansible
  ansible-vault create secure.yml
  ansible-vault rekey seucure.yml
  ansible-vault decrypt secure.yml
  ansible-playbook secure.yml --ask-vault-pass


