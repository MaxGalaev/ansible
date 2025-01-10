----
Запускать плейбук нужно вот так, с параметром --vault-id @prompt: 

ansible-playbook -i hosts.yml pve_create_vm.yml --vault-id @prompt
