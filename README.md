# ansible-rpirest

Ansible role to setup and deploy project [pirest-sense-hat](https://github.com/jregueirar/pirest-sense-hat)

test> ansible-playbook -i inventory test.yml

## Requirements

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

## Role Variables

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

## Dependencies

- ansiblebit.grafana

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }
	 
## TAGS

  * app_code: To deploy only change in the app code
  * configuration: To deploy only change in configuration
  * installation: To install all the necessary


License
-------

GPLv3

Author Information
------------------

- [jregueirar](https://github.com/jregueirar)
