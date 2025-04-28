# Cloud_1

This project automates the deployment of a cloud server using Ansible. I learn how to configure and manage infrastructures, deploy applications on remote servers, and ensure consistent environments through configuration management.

## Installation

Install Ansible and SSH utilities using Nix:

```bash
nix-shell -p ansible
nix-env -iA nixpkgs.sshpass
```

## Usage

Run the playbook with vault password prompt:

```bash
LC_ALL=C.UTF-8 ansible-playbook -i inventory.ini playbook.yml --ask-vault-pass
```



