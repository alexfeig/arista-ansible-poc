# An Ansible based POC to configure Arista switches.

I really need to add to this, but for now, please note that you need to add the following variables:

* `admin_secret` - this is a hashed password
* `admin_sshkey` - this is your SSH key
* `ansible_python_interpreter` - optional Python path, useful for homebrew

Install Ansible roles by running `setup.sh`
    
Also of note, I'm starting to add VLAN -> VXLAN mapping roles in for day2 ops.

## Requirements
You must use Ansible 2.2.0 for this. 2.2.1 does not work properly. Issue https://github.com/ansible/ansible/issues/21901 has been raised.

To ensure you have the proper version, use the following `pip` command: `pip install -U ansible==2.2.0.0`