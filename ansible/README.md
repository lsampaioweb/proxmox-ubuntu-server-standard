# proxmox-ubuntu-server-standard
Project with Ansible scripts to create an Ubuntu template on Proxmox from a cloned virtual machine with the default packages and updates.

### Manual Usage:

1. Change to the ansible directory.
    ```bash
    cd ansible
    ```

1. Install and setup application.
    ```bash
    ansible-playbook template.yml -e "hostname=ubuntu-24-04-server-standard"
    ```

1. Setup VM settings on Proxmox.
    ```bash
    ansible-playbook kvm_setup.yml -e "node=edge-pve-01 vm_name=ubuntu-24-04-server-standard"
    ```

#
### Created by:

1. Luciano Sampaio.
