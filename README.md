System Settings Configuration
=========

Configure System Settings for Junos.

Requirements
------------


Role Variables
--------------

system_settings: Dictionary containing settings for System


Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: junos_system_settings_config }

License
-------

BSD

Author Information
------------------

Marc Colburn Juniper
