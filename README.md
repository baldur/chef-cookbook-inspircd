Description
===========

Copyright 2012, AT&T Services, Inc.
All rights reserved.

Installs InspIRCd.

Target OS's: Ubuntu, Debian, Redhat, Centos

Requirements
============

* build-essential

Attributes
==========

Directories: 

* `node['inspircd']['dir']`
* `node['inspircd']['log_dir']`
* `node['inspircd']['pid']`

inspircd.conf values:

* `node['inspircd']['user']`
* `node['inspircd']['binary']`

Recipes
=======

default.rb - Use the default recipe to install inspircd via a source tarball.

Source build will enable the following modules:

* 
