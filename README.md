Apache
======

This is an Ansible role to install Apache package on RHEL and Debian.


Role Variables
--------------

This is the default variable.

```yaml
apache_security_options:
    servertokens: "Prod"
    serversignature: "Off"
    traceenable: "Off"
```

Actually, only security options is defined by default.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - clembruneteau.apache
```

License
-------

[MIT License](LICENSE)


