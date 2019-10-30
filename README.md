Role Name
=========

installs fzf package

Requirements
------------

git must be installed prior to use fzf role

Role Variables
--------------

fzf_install_path - defines fzf installation path (git will clone fzf there_
fzf_userlist     - the list of users fzf shall be installed for

default:
fzf_install_path:  "/usr/local/fzf"
fzf_userlist:       []

Dependencies
------------

-- none --

Example Playbook
----------------

how to use your role
    
1) define fzf_installation_path and fzf_user_list i.e. in ./group_vars/all/fzf.yml 
    fzf_userlist:
     - ubuntu
     - user
    fzf_install_path:  "/usr/local/fzf"

2) add the role to the playbook 

    - hosts: servers
      roles: 
        - role: taktus.fzf
          tags:
            - fzf


License
-------

BSD

Author Information
------------------

MarQ
# fzf
