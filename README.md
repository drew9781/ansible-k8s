# Ansible - k8s

This can deploy a kubeadm kubernetes cluster onto ubuntu VMs.

The order in which the playbooks should be ran is:
  -k8s.yml
  -k8s-master.yml
  -k8s-client.yml
