Ansible-zabbix-agent
--------------------

This is an gcavalcante8808/ansible-zabbix-agent repository with an Ansible Playbook.

Simple Usage
------------

Clone this repo into your server, access the folder created, create your hosts file and use the ansible-playbook to run it:

``` ansible-playbook -i hosts --extra-vars="zbx_server=myzabbixserver" playbook.yml ```

Vars:

zbx_server: FQDN or IP of your Zabbix Server, which will be included in the zabbix-agent configuration.

Playbook Support
----------------

This playbook is supported on Debian Family Systems and RHEL/Centos 7.

Author
------

Author: Gabriel Abdalla Cavalcante Silva (gabriel.cavalcante88@gmail.com)
