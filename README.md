logstash-packages
=================

[![Build Status](https://travis-ci.org/lsst-sqre/ansible-logstash-packages.svg?branch=master)](https://travis-ci.org/lsst-sqre/ansible-logstash-packages)

Install [Logstash](https://www.elastic.co/products/logstash) using [Ansible](http://docs.ansible.com/) for LSST SQuaRE infrastructure.

Example Playbook
----------------

    - hosts: server
      roles:
         - { role: lsst-sqre.logstash-packages }

Version
-------

Logstash version 5.x using the [Elastic repository](https://www.elastic.co/guide/en/logstash/5.0/package-repositories.html).

Tested using Ansible 2.1 which is currently in development.

License
-------

The MIT License. See the [LICENSE file](https://github.com/lsst-sqre/ansible-logstash-packages/blob/master/LICENSE).
