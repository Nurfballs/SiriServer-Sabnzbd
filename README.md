sabnzbd.py
============

Description
-----------
This plugin will allow you to use Siri in conjunction with SiriServer, to perform actions with Sabnzbd+ via voice commands.


Pre-requisites
--------------
1. A working installation of SiriServer.
2. A working installation of Sabznbd+.

The installation and configuraiton of the pre-requisites are outside the scope of this readme. 

If you do not have these applications configured, please seek further instruction from the installation guides for each application.


Installation
------------
1. Download `sabnzbd.py` and place it in your `/plugins` directory.
3. Edit `sabnzbd.py` and add the IP Address, Port and API Key of your Sabnzbd+ installation.
2. Edit your `plugins.conf` and add `sickbeard` to the list of plugins to load.
3. Restart your SiriServer.

Functions
---------

This script supports the following functions

* Display current download queue and statistics
* Pause / Resume queue

**Display current download queue and statistics**

Listen String: `*(sab|sabnzbd|download).*(queue|q|status|stats|statistics)*`

Example: say `download queue` or `sab status` or `download statistics` etc.

[Screenshot](http://i.imgur.com/Dh2Wb.png "Screenshot")


**Pause Sabnzbd+ downloads**

Listen String: `(sab|sabnzbd|download|downloads) (pause|stop)`

Example: say `download pause` or `sab stop` etc


**Resume Sabnzbd+ downloads**

Listen String: `(sab|sabnzbd|download|downloads) (resume|unpause|start)`

Example: say `download resume` or `sab unpause` etc.

[Screenshot](http://i.imgur.com/L3pM8l.png "Screenshot")


Version History
---------------

**0.2**

**0.1**

* Initial Release
