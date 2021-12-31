# Kubernetes Kubeadm Ansible playbook

Here is the playbook used to prepare hosts for a kubeadm Kubernetes install

## How to use

We are assuming that you have ansible installed already.

1, Clone this repo  
```bash
git clone ...
```

2, Install the roles
```bash
ansible-galaxy install -r roles/requirements.yml --roles-path roles
```
