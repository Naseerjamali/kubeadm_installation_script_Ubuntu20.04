# kubeadm_installation_script_Ubuntu20.04
I was playing around with Kubeadm in a Virtual Machine, everytime I spawn it I would have to type the commands and it took lot of time.
I decided to create a bash script and automate the Kubeadm installation.
This works for Ubuntu 20 version.
After the script is executed - you can run "sudo kubeadm init --pod-network-cidr=192.168.0.0/16" to create the cluster.

Thanks!
