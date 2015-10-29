=============================
ZenPacks.community.WinServices
=============================


Description
===========
This ZenPack is built entirely through the GUI to demonstrate adding Windows services to a ZenPack.


Features
========

Windows Services
-----------

* TapiSrv Windows service


Requirements & Dependencies
===========================

* Zenoss Versions Supported:  3,x, 4.x
* External Dependencies: 
* ZenPack Dependencies: 
* Installation Notes: 

  - Restart zenoss entirely after installation       or 
  - For Zenoss Core 3.x and 4.x, restart zenhub and zopectl
  - For Zenoss Service Dynamics, restart zenoss entirely after installation
  - For Zenoss 5, restart zenoss entirely after installation


Download
========
Download the appropriate package for your Zenoss version from the list
below.

* Zenoss 4.0+ `Latest Package for Python 2.7`_

ZenPack installation
======================

This ZenPack can be installed from the .egg file using either the GUI or the
zenpack command line. 

To install in development mode, find the repository on github and use the *Download ZIP* button
(right-hand margin) to download a tgz file and unpack it to a local directory, say,
/code/ZenPacks .  Install from /code/ZenPacks with::
  zenpack --link --install ZenPacks.community.WinServices
  Restart zenoss after installation.


Limitations and Troubleshooting
===============================

Note that adding services to a ZenPack also results in adding any service *instances* that
exist in the current Zenoss installation.  Installing the ZenPack on a different Zenoss
will result in error messages, though the Zenpack **will** install correctly and will **not**
include the instances.



Change History
==============
* 1.0.0
   - Initial Release


.. External References Below. Nothing Below This Line Should Be Rendered

.. _Latest Package for Python 2.7: https://github.com/jcurry/ZenPacks.community.WinServices/blob/master/dist/ZenPacks.community.WinServices-1.0.0-py2.7.egg?raw=true
