# ansible-rpirest

Ansible role to setup and deploy the project [rpirest](https://github.com/jregueirar/rpirest)

ansible-rpirest/tests> ansible-playbook -i inventory test.yml

## Requirements


## Role Variables

You have a complete list in defaults/main.yml. 

## Dependencies


## Example Playbook

    - hosts: all
      remote_user:pi
      become:yes
      roles:
         - ansible-rpirest
	 
## TAGS

  * installation: To install all the packages, dependencies and code.
  * app_code: To deploy only change in the app code. This not include changes in the requirements or packages dependencies. 
  * configuration: To deploy only change in configuration
  * nginx: To install and configure only nginx
  * fqdn: To change de hostname

 
License
-------

GPLv3

 Author Information
------------------

- [jregueirar](https://github.com/jregueirar)