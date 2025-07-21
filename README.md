# VM Setup

This project uses Ansible to set up and provision virtual machines.

## Prerequisites

- Ansible
- A virtual machine provider (e.g., VirtualBox, VMware)

## Usage

1.  Update the `inventory/hosts.ini` file with your server details.
2.  Modify the variables in `group_vars/all.yml` as needed.
3.  Run the playbook:

    ```bash
    ansible-playbook site.yml
    ```
