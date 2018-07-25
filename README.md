Role Name
=========

This role mirrors your local syncthing directory setup to an SSH-accessible Debian Linux computer

Requirements
------------

Thank you to @classicsc for the library, which I modified to produce JSON output.

Install it:
```bash
pip3 install git+https://github.com/oneyb/syncthingmanager
```

Role Variables
--------------

Edit inventory to taste.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

 - inventory file contents:
localhost          ansible_user=me
box.local          ansible_user=otherme
raspberrypi.local  ansible_user=pi

License
-------

GPLv3

