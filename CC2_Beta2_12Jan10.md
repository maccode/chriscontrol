# ChrisControl Version 2 Beta 2 - 12 January 2010 #

## Change History ##

### Beta 2 - 12 Jan 10 ###
  * Removed duplicate name to IP resolution code
  * Only remove VNC if VNC protocol selected
  * Tweak VNC launch command to always use IP address
  * Added hostname resolution check and prompt
  * Host field re-instated on WOL tab (Fixes [Issue #1](https://code.google.com/p/chriscontrol/issues/detail?id=#1))
  * RDP launch & loop tweaked to use MSTSC PID tracking

### Beta 1 - 06 Jan 10 ###
  * MSTSC location & version handling - RDP launch tweaked with double button presses
  * VNC loop modified for new VNC viewer + spawned VNC PID tracking
  * RDP client (mstsc.exe) longer contained in chriscontrol.exe. (All modern Windows O/S have RDP client installed as part of O/S.) If an RDP client is required, one can easily be downloaded from [here](http://support.microsoft.com/kb/969084)
  * New version of Ultr@VNC included - v1.0.8.2
  * Lots of small code tweaks to enable source to run and compile using AutoIt v3.3.2.0


## To Do ##
  * Remote Host firewall open for VNC.  Required if remote system has firewall enabled as well as file & printer sharing
  * Test cmd line
  * Test WOL
  * Update help file


# Please post all Problems / Requests on Issues Page (Issues tab above) #