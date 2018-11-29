# memcached

[![Build Status](https://travis-ci.com/iroquoisorg/ansible-role-memcached.svg?branch=master)](https://travis-ci.com/iroquoisorg/ansible-role-memcached)

Ansible role for memcached

This role was prepared and tested for Ubuntu 16.04.

# Installation

`$ ansible-galaxy install iroquoisorg.memcached`

# Default settings

```

memcached_port: 11211
memcached_listen_ip: 127.0.0.1

memcached_memory_limit: 128
memcached_connections: 1024

memcached_log_file: /var/log/memcached.log
memcached_log_verbosity: ""

```
