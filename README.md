spotify
=======
[![Ansible Lint](https://github.com/oxivanisher/role-spotify/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/oxivanisher/role-spotify/actions/workflows/ansible-lint.yml)

This role installs the Spotify app from flatpak or snap. If both package managers are available, it will prefer flatpak.

Role Variables
--------------

None.

Example Playbook
----------------
```yaml
- name: Install spotify
  hosts: clients
  roles:
    - role: oxivanisher.linux_desktop.spotify
```

License
-------

BSD

Author Information
------------------

This role is part of the [oxivanisher.linux_desktop](https://galaxy.ansible.com/ui/repo/published/oxivanisher/linux_desktop/) collection, and the source for that is located on [github](https://github.com/oxivanisher/collection-linux_desktop).
