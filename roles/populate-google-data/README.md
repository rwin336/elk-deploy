Role Name
=========

The "Learning ELK Stack" book relies on populating Elasticsearch with Google's stock data.  This role populates that data into elasticsearch.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

    - hosts: all
      roles:
        - fireup-elasticsearch
        - populate-google-data

License
-------

Apache 2

Author Information
------------------

R.A. Winters<rwin336@gmail.com>
