# ansible-rpirest

Ansible role to setup and deploy project [pirest-sense-hat](https://github.com/jregueirar/pirest-sense-hat)

ansible-rpirest/tests> ansible-playbook -i inventory test.yml

## Requirements


## Role Variables


## Dependencies

- geerlingguy.nginx

## Example Playbook

    - hosts: all
      remote_user:pi
      become:yes
      roles:
         - ansible-rpirest
	 
## TAGS

  * app_code: To deploy only change in the app code. This not include changes in the requirements or packages dependencies. 
  * configuration: To deploy only change in configuration
  * installation: To install all the packages, dependencies and code.


License
-------

GPLv3

Author Information
------------------

- [jregueirar](https://github.com/jregueirar)
