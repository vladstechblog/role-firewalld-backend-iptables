role-firewalld-backend-iptables
=========

Changes firewalld backend to iptables

Requirements
------------

System supports iptables

Role Variables
--------------

- `firewalld_config_path`: path for firewalld configuration file

Dependencies
------------

N/A

Example Playbook
----------------

```yaml
- hosts: servers
  become: true

  roles:
    - role: 
```

License
-------

BSD

Author Information
------------------

https://vlads.tech