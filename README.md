# vagrant-docker-swarm-cluster-project
In this project challenge we create a local Swarm cluster, using virtual machines provisioned with Vagrant

Step by step:

. Create a vagrantfile with the definitions of 3 virtual machines: being the first machine with the name of master and the other ones with the name of node01 and node02;
. Each virtual machine must have a fixed IP;
. All VMs must have Docker pre-installed;
. The machine named master must be the cluster manager node;
. The other machine must be added to the Swarm cluster as Workers.
