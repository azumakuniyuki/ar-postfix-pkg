Ansible Role: Postfix(pkg)
================================================================================
Install and configure Postfix as an SMTP Server

- Install Postfix
  - version 2.10.1 using yum at CentOS 7
  - version 3.1.9 using apt at Debian 9.8
- Configure files in /etc/postfix
- Open tcp/25 and tcp/587

Requirements
--------------------------------------------------------------------------------
None

Role Variables
--------------------------------------------------------------------------------
The following variables are defined in defaults/main.yml file.

```yaml
postfix:
```

Dependencies
--------------------------------------------------------------------------------
None

Example Playbook
--------------------------------------------------------------------------------
```yaml
- hosts: servers
  roles:
     - { role: azumakuniyuki.ar-postfix-pkg }
```

License
--------------------------------------------------------------------------------
BSD

Author Information
--------------------------------------------------------------------------------
[azumakuniyuki](https://nyaan.jp)

