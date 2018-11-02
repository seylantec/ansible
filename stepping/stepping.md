This checks for multiple tasks and skips the respective task and continues

ansible-playbook stepping.yml  --start-at-task='Installing Emacs' --check

# This executes each task from the point
ansible-playbook stepping.yml --step 


