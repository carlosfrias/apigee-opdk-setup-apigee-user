Apigee OPDK Setup Apigee user
=========

This roles makes sure that the apigee user and ssh keys is setup on the system. 

Requirements
------------

The installation of Apigee OPDK requires root access. Credentials must also be supplied to override the empty placeholders
provided here. It is recommended that credentials be consolidated into a single credentials.yml file that can be stored 
separately. It is assumed that files containing credentials are stored in the ~/.apigee folder. 


Role Variables
--------------

This role uses variables defined in the role apigee-opdk-setup-default-settings

Dependencies
------------

This depends on the following roles:

* apigee-opdk-setup-default-settings.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: apigee-opdk-setup-apigee-user }

License
-------

Apache License Version 2.0, January 2004

Author Information
------------------

Carlos Frias
<!-- BEGIN Google Required Disclaimer -->

# Not Google Product Clause

This is not an officially supported Google product.
<!-- END Google Required Disclaimer -->
