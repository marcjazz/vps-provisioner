# VM Setup

This project uses Ansible to set up and provision virtual machines.

## Prerequisites

- Ansible. `ansible-playbook` is part of the Ansible distribution. If you don't have it, please follow the [official installation guide](https://docs.ansible.com/ansible/latest/installation_guide/index.html).
- A virtual machine provider (e.g., VirtualBox, VMware)

### Installing Ansible on Ubuntu

To install Ansible on Ubuntu, you can use the following commands:

```sh
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install ansible
```

## Usage

1.  Update the `inventory/hosts.ini` file with your server details.
2.  Modify the variables in `group_vars/all.yml` as needed.
3.  Run the playbook:

    ```sh
    ansible-playbook site.yml
    ```
