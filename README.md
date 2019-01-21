[![Build Status](https://travis-ci.org/pescobar/ansible-role-lmod.svg?branch=master)](https://travis-ci.org/pescobar/ansible-role-lmod)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-pescobar.lmod-blue.svg)](https://galaxy.ansible.com/pescobar/lmod)

ansible-role-lmod
=========

Install Lmod package from EPEL repo and configures it using environment variables in a profile file "/etc/profile.d/zzz_lmod_settings.sh"


Requirements
------------

None

Role Variables
--------------

```
LMOD_AUTO_SWAP: false

LMOD_CACHED_LOADS: true

LMOD_CASE_INDEPENDENT_SORTING: true

LMOD_DISABLE_NAME_AUTOSWAP: true

LMOD_EXACT_MATCH: true

LMOD_MPATH_AVAIL: true

LMOD_PIN_VERSIONS: true

LMOD_MODULEPATH: "/soft/modules/all"

LMOD_ADD_EPEL_REPO: true
```

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: pescobar.lmod }

License
-------

GPLv3

Author Information
------------------

Pablo Escobar Lopez
