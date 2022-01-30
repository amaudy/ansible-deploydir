Ansible Role for create deploy folder
=========

Ansible Role for create deploy folder


Role Variables
--------------

```
deploy_dir: '/var/www/'
project_name: 'foobar'
```

From variables above. This script will create folder '/var/www/foobar', '/var/www/foobar/share' and '/var/www/foobar/share/config'

Dependencies
------------

Should work together with role "amaudy.deployer"

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - amaudy.deploydir

License
-------

BSD

Author Information
------------------

WIP.
