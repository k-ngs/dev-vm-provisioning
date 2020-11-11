# dev-vm-provisioning
Provisioning development machine(Ubuntu18.04) by Ansible

## Install Ansible tools
At first, you have to execute this script.
```
$ install_ansible.sh
```

## Execute Ansible playbook
```
$ ansible-playbook -i inventory.yml site.yml
```