----
Запускать плейбук нужно вот так, с параметром --vault-id @prompt: 

ansible-playbook -i hosts.yml create_docker_swarm_vm.yml -u root --vault-id @prompt
