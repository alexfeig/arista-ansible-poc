# Ansible Playbook for EOS

I really need to add to this, but for now, please note that you need to add the following variables:

* `admin_secret` - this is a hashed password
* `admin_sshkey` - this is your SSH key
* `ansible_python_interpreter` - optional Python path, useful for homebrew

Install Ansible roles: 

    sudo ansible-galaxy install -r galaxy-roles.txt