Ansible Role helm
=========

<Description>

Releases: <Link to versions>

Role Variables
--------------


Supported OS
------------

A list of operating systems that have been verified on

* Ubuntu 16.04 (xenial)
* Ubuntu 18.04 (bionic)
* Ubuntu 20.04 (focal)
* Ubuntu 21.04 (hirsute)
* Ubuntu 21.10 (impish)
* Debian 9 (stretch)
* Debian 10 (buster)
* Debian 11 (bullseye)
* Debian 12 (bookworm)


Example Playbooks
----------------

Minimal:
```
- name: Install CLI
  hosts: all
  roles:
    - role: exzeo.helm
```

Specific Version:
```
- name: Install CLI
  hosts: all
  roles:
    - role: exzeo.helm
      vars:
        helm_version: "1.22.4"
```

Uninstall:
```
- name: Install CLI
  hosts: all
  roles:
    - role: exzeo.helm
      vars:
        uninstall: true
```