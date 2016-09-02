fireup-elasticsearch
=========

This role uses Docker to create a container for elasticsearch.  The container expsoses the normal eleasticsearch ports and installs kopf.


Requirements
------------

* Ansible 2.1.0 or higher for docker_container
* Python 2.7 or higher
* Docker.py

Role Variables
--------------

None

Dependencies
------------

None


Example Playbook
----------------

     ---
     - hosts: all
       roles:
         - fireup-elasticsearch

License
-------

Apache 2


Author Information
------------------

R.A. Winters <rwin336@gmail.com>
