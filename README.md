Role Name
=========
gwenlei.rails-unicorn

Requirements
------------
ubuntu16.04 xenial

Role Variables
--------------
defaults/main.yml

app_name: demo
unicorn_workers: 2
unicorn_timeout: 15

Dependencies
------------
none

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: gwenlei.rails-unicorn }

License
-------
MIT

Author Information
------------------
onecloud
