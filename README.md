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

Example Playbook
----------------

Example inventory:

 - inventory file contents:
```yaml
localhost          ansible_user=me
box.local          ansible_user=otherme
raspberrypi.local  ansible_user=pi
```

Running this on the one server you need:
```bash
ansible-playbook -i box.local, syncthingmanages.yaml --ask-become-pass -u User-Name
```

License
-------

GPLv3

