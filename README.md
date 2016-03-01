votum.vagrant-gitconfig
=======================

Copies the local git config into the vagrant users home on the box.

Requirements
------------

None. 

Role Variables
--------------

* votum_vagrant_gitconfig_path_local

   the path to the local .gitconfig file
  
* votum_vagrant_gitconfig_filemode

   the filemode for the .gitconfig file when copied to vagrant's home
  
* votum_vagrant_home_dir

   the vagrant's user home directory

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: votum.vagrant-gitconfig }

License
-------



Author Information
------------------

VOTUM GmbH
