ansible-logstash
================

[![Build Status](https://travis-ci.org/jmatt/ansible-logstash-packages.svg?branch=master)](https://travis-ci.org/lsst-sqre/ansible-logstash-packages)

Install logstash using Ansible for LSST SQuaRE infrastructure.

Example Playbook
----------------

    - hosts: server
      roles:
         - { role: jmatt.logstash.packages }

License
-------

The MIT License. See the [LICENSE file](https://github.com/lsst-sqre/ansible-logstash-packages/blob/master/LICENSE).
