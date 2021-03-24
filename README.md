# HomelabScripts-
Collection of the various services / scripts I have deployed in my homelab 

Overview of Documents:

DHCPD: Short DHCP Server config that provides PXE Boot services and also runs address assignment for home network

Playbooks: Experiments with Ansible, main goal is to create a playbook that can deploy k8s automatically (I have one role for kube control nodes and one role for kube worker nodes) and also segregate everything into proper roles and write it following ansible best practices

Pxelinux.cfg This sets up the PXE Boot server and autoboots Ubuntu 18.04 LTS server install but it has options for CentOS and diagnostic/recovery tools like clonezilla

Ubuntu PXE File was templated from Ubuntu documentation and allows me to automatically deploy ubuntu on servers combined with the PXE Boot Server

Projects Im working on:

Trying to get kubernetes script finished and polished

Trying to deploy actual services once k8s script is finished

Work on getting full DNS resolution for homelab set up

Work on getting proper L3 seperation of the network in house and move off singular l2 domain

Work on getting a more flexible pxe boot system (cobbler maybe?) 

