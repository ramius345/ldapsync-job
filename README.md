# Ansible applier playbook for setting up ldap group sync.

## Installation

### Install Prereqs
ansible-galaxy install -r requirements.yaml -p galaxy

### Run playbook
ansible-playbook -i applier galaxy/openshift-applier/playbooks/openshift-cluster-seed.yml


