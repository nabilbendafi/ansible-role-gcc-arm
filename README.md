gcc-arm
=======

This role installs GNU C Compiler for ARM

Installation
------------

```
$ ansible-galaxy install nabilbendafi.ansible-role-gcc-arm
```

```
# gcc-arm.yml
- hosts: localhost
  roles:
    - nabilbendafi.gcc-arm
```

```
$ ansible-playbook psptoolchain.yml
```

Dependencies
------------

None

License
-------

[MIT](LICENSE.txt)

Author Information
------------------

[Nabil Bendafi](https://github.com/nabilbendafi)
