Commands for CREATE/REMOVE users
ansible-playbook ./create_users.yaml  --vault-password-file key.txt
ansible-playbook ./remove_users.yaml  --vault-password-file key.txt


key.txt file is included key for decrypt users.yaml file
users.yaml file is included encrypted data of five users