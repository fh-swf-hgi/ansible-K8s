# ansible-K8s
https://www.digitalocean.com/community/tutorials/how-to-create-a-kubernetes-cluster-using-kubeadm-on-debian-9


To run on master node:
printf "[defaults]\nallow_world_readable_tmpfiles=true\n" > ~/.ansible/ansible.cfg
export ANSIBLE_CONFIG=~/.ansible/ansible.cfg 
