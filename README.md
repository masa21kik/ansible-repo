# Ansible-repo

## Usage

Apply playbook,

    $ ansible-playbook -K -i hosts base-playbook.yml

Dry-run playbook,

    $ ansible-playbook -K -i hosts base-playbook.yml --check

Check syntax of playbook,

    $ ansible-playbook -K -i hosts base-playbook.yml --check-syntax
