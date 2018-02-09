foreman_repositories
=========

Configure Foreman yum repository.</br>
The role was copied from the [theforeman/forklift project](https://github.com/theforeman/forklift/tree/master/roles/foreman_repositories).

Requirements
------------

Role Variables
--------------

| Name    | Description    | Required    | Default    | Values | Examples |
|:--|:--|:-:|:-:|:-:|:--|
| foreman_repositories_version | Foreman version | No | nightly | - | nightly |
| foreman_repositories_release | Foreman environment | No | release | - | release |

Dependencies
------------

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: genadipost.foreman_repositories }

License
-------

BSD

Author Information
------------------

genadipost@gmail.com
