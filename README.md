# vagrant to setup K8s cluster using oracle virtual box in windows 

# Prerequsities 
1. Oracle Virtual Box
2. Vagrant
3. GIT bash

# Command
download the vagrant file and issue
vagrant up


# kubenetes initialization 
1. vagrant ssh master
2. sudo kubeadm init --apiserver-advertise-address=192.168.57.10 --pod-network-cidr=10.244.0.0/16

follow the instruction from the above output

# Flannel CNI (Container Network Interface) plugin after Kubernetes initialization.
kubectl apply -f https://raw.githubusercontent.com/flannel-io/flannel/master/Documentation/kube-flannel.yml




   
