Signal
=========

Installs and configures Signal for the user.

Requirements
------------

To include this role in your `requirements.yml` file, add the following list item:

```yaml
---
roles:
  - name: whalej84.signal
    src: https://github.com/WhaleJ84/ansible-role-signal.git
    scm: git
```

Example Playbook
----------------

This example playbook shows how I would use this role, with custom variables to suit my needs.

```yaml
---
- hosts: localhost

  roles:
    role: whalej84.signal
    tags: [ signal ]
```

