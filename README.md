systemd_resolved
=========

Configures systemd-resolved with a minimum feature-set without offerring too many bells and whistles.

Role Variables
--------------

Are documented in `defaults/main.yml`.

Example Playbook
----------------
```yaml
- hosts: servers
  tasks:

     - ansible.builtin.import_role:
         name: systemd_resolved
```
