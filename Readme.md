# Cloud_1

This project automates the deployment of a cloud server using Ansible. I learn how to configure and manage infrastructures, deploy applications on remote servers, and ensure consistent environments through configuration management.


# Commands
nix-shell -p ansible

nix-env -iA nixpkgs.sshpass

LC_ALL=C.UTF-8 ansible-playbook -i inventory.ini playbook.yml --ask-vault-pass
