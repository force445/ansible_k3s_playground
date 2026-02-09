# Ansible script for k3s, k8s installation and uninstallation

- [hosts](./cluster/hosts.yaml) This file is for specific host to ansible's operation.

# Roles

- The k3s roles and task is for k3s installation.
- installation script is from k3s document so if there are something to modify please go to k3s document and modify as you like.
- The main.yamlis for considolate all tasks together

# Playbooks

[main_playbook](site.yaml) this is the main playbook for installation