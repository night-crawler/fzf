Role Name
=========

nstall fzf package

Requirements
------------

git must be installed and executable prior to use fzf role

Role Variables
--------------

fzf_install_path - defines fzf installation path (git will clone fzf there
fzf_userlist     - the list of users fzf shall be installed for

default:
fzf_install_path:  "/usr/local/fzf"
fzf_userlist:       []

Dependencies
------------

-- none --

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles: fzf

License
-------

BSD

Author Information
------------------

MarQ
# fzf
