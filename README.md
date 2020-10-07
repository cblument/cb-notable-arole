cb-notable-arole
=========

Installs the [Notable Application](https://notable.app/).

Requirements
------------

Run this role as the user that you intend the app as (Not the root user).  If root access is required the tasks will utilize sudo as need

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

    ansible-playbook -i localhost, --ask-become-pass

    - hosts: localhost,
      roles:
         - cb-notable-arole

License
-------

BSD

Author Information
------------------

