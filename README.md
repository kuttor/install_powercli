install_powercli
=========

This Ansible Role installs Nuget and PowerCli.


Requirements
------------

- Ansible 2.5+
- Python 2.7/3.X
- Windows 2012/2016 image

Role Variables
--------------

```
temp_folder: C:\Windows\Temp
```

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - install_powercli
```

Author Information
------------------

- name: Andrew Kuttor
- email: andrew.kuttor@gmail.com