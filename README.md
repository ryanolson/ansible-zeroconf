ansible-zeroconf
================

Enables the host to publish it's hostname to the local Bonjour / mDNS service on the network.

Currently works for Ubuntu 14.04.03.


Example Playbook
----------------

```
    - hosts: servers
      roles:
         - { role: ryanolson.ansible-zeroconf }
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
