Description
===========

Installs [LXC](http://lxc.sourceforge.net/) packages.

Platform
============

The following platforms have been test with this cookbook:

* Ubuntu (12.04)

Attributes
==========

* `set['lxc']['packages']`  - List of packages to install for LXC.

Usage
=====

* `recipe[lxc]`

* `sudo lxc-create -t ubuntu -n my-container`
* `sudo lxc-start -n my-container`

License
=======

See LICENSE file.
