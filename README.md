vim role
=========

Install Vim and other plugins, syntax highlighters et. al.

Requirements
------------

None

Role Variables
--------------

```yml
# syntax highlighting plugins
VIM_SYNTAX_PLUGINS: []

# plugins installed by pathogen
VIM_PLUGINS: []
```

Dependencies
------------

None

Example Playbook
----------------

```yml
- hosts: servers
  roles:
     - WizDevOps.vim-ansible-role
```

License
-------

GPLv3

Author Information
------------------

Daniel Andrei Minca <dminca@protonmail.com>
