Role Name
=========

This is a type of installtion of Nginx websever on RHEL and UBUNTU servers, at a same time with test webpage

Requirements
------------
Server needs to be online
First run this command for your UBUNTU server "ansible -m command -a 'sudo apt-get purge nginx nginx-core nginx-common'" 
Check the hosts

Role Variables
--------------
There is an index.html.j2 file templates so check that  out it's for both the type of distribution

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      become: yes
      roles:
         - webserver_installation

License
-------

BSD

Author Information
------------------
Deepak Shinde (Danny)
Email: Deepaksh027@gmail.com
LinkedIN: https://www.linkedin.com/in/deepak-shinde-a94199149/

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
