Node Bootstrap
=========

The purpose of this role is to provide a universal methodology for provisioning new nodes operated in the Chainflip network.
This role should be referenced at the top of any ansible playbook so that we can make sure we have secured the most basic requirements.


Requirements
------------

Primarily we provision nodes using the `Ubuntu 20.04 Focal` release. The playbooks are largely written with this in mind.

Role Variables
--------------


Dependencies
------------


Example Playbook
----------------

    - hosts: servers
      roles:
         - node_bootstrap

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
