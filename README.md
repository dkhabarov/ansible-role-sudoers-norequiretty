# ansible-role-sudoers-norequiretty
Ansible role for disabling requiretty setting in /etc/sudoers. (Requirement for Ansible pipelining)

## Installation

Write to requirements.yml

        - src: https://github.com/dkhabarov/ansible-role-sudoers-norequiretty.git
          name: dkhabarov.ansible-role-sudoers-norequiretty

Run install command:

        ansible-galaxy install -i -f -r requirements.yml
