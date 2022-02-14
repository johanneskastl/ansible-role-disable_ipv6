disable_ipv6
=========

Disable IPv6 completely.

Obviously, IPv6 is the future and you should totally use it. But there are environments or occasions where you might want to completely disable it. Demos, training setups, ...

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: 'johanneskastl.disable_ipv6' }

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
