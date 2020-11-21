Automated install metricbeat
=========

This role made a instalation of metricbeat on the list of servers, start and enable it. 

Requirements
------------

This role install curl if not exists.
Role Variables
--------------

IpKibana : you need to put the ip and the port for kibana, for example "192.168.0.2:5601"
IpElasticsearch : you need to put the ip and the port for elasticsearch, for example "192.168.0.2:9200"
Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      vars:
	IpKibana: 192.168.0.1:5601
	IpElasticsearch: 192.168.0.1:9200
      roles:
         - { role: metricbeat }

License
-------

BSD

Author Information
------------------

