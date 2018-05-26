# Mac Ansible Playbook

Forked from: https://github.com/geerlingguy/mac-dev-playbook

For installation:

    $ xcode-select --install
    $ sudo easy_install pip
    $ sudo pip install ansible
    $ mkdir git && cd git
    $ git clone https://github.com/angryninja48/mac-dev-playbook.git
    $ cd mac-dev-playbook
    $ ansible-galaxy install -r requirements.yml

    For Ansible < 2.0
    $ ansible-playbook -i inventory --ask-sudo-password main.yml
    For Ansible >= 2.0 use
    $ ansible-playbook -i inventory --ask-become-pass main.yml
