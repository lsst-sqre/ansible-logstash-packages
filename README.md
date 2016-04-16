ansible-logstash
================

[![Build Status](https://travis-ci.org/jmatt/ansible-logstash.svg?branch=master)](https://travis-ci.org/lsst-sqre/ansible-logstash)

Install logstash using Ansible for LSST SQuaRE infrastructure.

Example Playbook
----------------

    - hosts: server
      roles:
         - { role: jmatt.logstash }

License
-------

See the [LICENSE file](/LICENSE).
