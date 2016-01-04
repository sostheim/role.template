role.template
========

A template to use for implementing roles.

**Instructions**

To use this template:

1. Clone this repository
2. Rename this repository, remove the .git directory
3. Publish or Private? Add or remove the Apache license details depending on wether or not you plan to make this available publicly. 
4. Find and replace every instance of the template parameters \{ role \}, \{ role_name \}, \{ role_args \}, etc... with the name of the role you are createing.
5. Implement your role logic (tasks/main.yml)
6. Test
7. Create a new Github repository for your role
8. Optionally: Create a new Ansible Galaxy Role for your repository (udpate meta/main.yml)

**Example Play**:
```
---
- name: Run role.template
  hosts: host-or-groupname
  roles:
    - role.template
```

Usage
-----

Document roles' usage, in particular required and optional arguments that can be supplied to the role.
```
```

Requirements
------------

Document roles' reqirements, if any.
```
```

Constant Role Variables
-----------------------

Document roles' constant varialbe, if any, that exist in ./vars/main.yml
```
```

Role Variables
-----------------------

Document roles' variables, if any, that exist in ./defaults/main.yml 
```
```

Dependencies
------------

Document roles' dependences, if any, that exist in ./meta/main.yml.
```
```

Testing
-------

Document roles' test facilites and unit tests.
```
```

License
-------

Apache v2.0
