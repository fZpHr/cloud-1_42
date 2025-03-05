nix-shell -p ansible
nix-env -iA nixpkgs.sshpass
LC_ALL=C.UTF-8 ansible-playbook -i inventory playbook.yml