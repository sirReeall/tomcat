tomcat
=========
[![Build Status](https://travis-ci.org/sirReeall/tomcat.svg?branch=master)](https://travis-ci.org/sirReeall/tomcat)

Currently this role only download the require tomcat version for ACS 6.1.

Requirements
------------

Tomcat requires that Java is installed. The Tomcat requirements can be found here [link](https://tomcat.apache.org/tomcat-8.0-doc/setup.html)

I have created an Ansible role that can install Java, this can be used in comination with this role. You can find this in either GitHub [link](https://github.com/sirReeall/java)

Role Variables
--------------

Installation directory for tomcat
    tomcat_install_folder: /opt/tomcat

User that will own the tomcat_install_folder recursively
    tomcat_user: tomcat

Example Playbook
----------------

License
-------

Free
