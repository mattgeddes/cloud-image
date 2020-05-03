cloud-image
===========

An Ansible role for downloading and managing cloud-init operating system images.

Doesn't yet validate file checksums.

Role Variables
--------------

TODO

Requirements
------------

Assumes that qemu-img is installed and that there is reachability to the repository containing the cloud-init images.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

Apache-2.0

