This role was work-in-progress and it is currently archived.

The role was able to start to setup Skynet Webportal at the git commit
`7ec5e5106fd3` (without paid accounts).

In the current status the role is able to configure MongoDB keyfile, but it is
not able to update MOngoDB keyfile on the next executions if the keyfile is
updated.

MongoDB initialization must be in sync with docker-compose.yml if the MongoDB
docker-compose configuration changes later.

Role Name
=========

Ansible role to install Skynet Webportal.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
