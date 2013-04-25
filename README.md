growl-uos
=========

Growl for UoS use.

This is a fork of https://github.com/irium/growl-win-8, which modifies the Growl for Windows code to work in Visual Studio 2012.


Supports a /nogui:true command line parameter, which forces the use of DisplayNone. This allows the software to be run headless as a scheduled task, or with srvany (untested), etc.