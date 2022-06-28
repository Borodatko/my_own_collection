Create-role
=========

Role creates file with content.


Role Variables
--------------

There are two variables:

```yaml
file_path: ./example.txt       # Use for specific file path
file_content: "Hello World\n"  # Use for specific content
```


Example Playbook
----------------

An example of using role:

```yaml
- hosts: all
  roles:
    - create-role
```

License
-------

BSD-3-Clause

Author Information
------------------

Orlov Dmitriy
