# An Ansible based POC to configure Arista switches.

Please note that you need to add the following variables:

* `admin_secret` - this is a hashed password
* `admin_sshkey` - this is your SSH key
* `ansible_python_interpreter` - optional Python path, useful for OS X homebrew Python installations

Install Ansible roles by running `setup.sh`

Edit the inventory file and variable files for your desired configuration.

## Running it

To run, use `ansible-playbook`: `ansible-playbook -i hosts site.yml`

## Requirements
You must use Ansible 2.3 or greater for this. 2.2.1 does not work properly. 