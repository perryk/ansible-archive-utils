archive-utils
=========

[![pipeline status](https://gitlab.com/devoperate/ansible-archive-utils/badges/master/pipeline.svg)](https://gitlab.com/devoperate/ansible-archive-utils/commits/master)

Ansible role that installs common archive utilities on Linux.

Requirements
------------

You just need a target host that Ansible can control.

Role Variables
--------------

See vars.

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - { role: devoperate.archive-utils }
```

License
-------

See LICENSE.

Author Information
------------------

- [Claude Léveillé](https://claude-leveille.com)
