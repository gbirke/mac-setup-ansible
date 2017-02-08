# Ansible Mac Setup

Ansible playbooks to set up my Macs

## Usage

Run `bootstrap.sh`

Run `ansible-playbook --ask-sudo-pass -i private.ini site.yml`

## TODO
- Refactor different environments: Have different variable files for different computers, rename `private` role to `extra` and include variable file depending on host.
- Set up dotfiles
- Add tests

## Thanks
This wouldn't have been possible without the following articles/code sources:
- http://il.luminat.us/blog/2014/04/19/how-i-fully-automated-os-x-with-ansible/
- https://github.com/geerlingguy/mac-dev-playbook
