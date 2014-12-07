### Documentum xCP Demo

This is a little demo application, built using Documentum xCP developer edition. The demo implements an application aimed to universities to help them catalog its faculties/schools and related courses.


#### Tentative GitIgnore
I did not find a pure xCP gitignore to copy, so I built one based on Eclipse and xCP Designer Help Version 2.1 User Guide. Let me know if you find problems.


#### Environment

This is the environment necessary to build and run the demo

Component | Description
----------|------------
Documentum Server | Documentum 7.1 Developer Edition
Server OS | Linux CentOS (VM)
Server VM memory | 10Gb
Documentum xCP Designer Workstation | Windows 7 64, 6Gb memory


#### Required Running Services
I needed to start these services manually before application deployment. After starting all services, my VM consumed 8Gb, this is the reason I am recommending 10Gb for the VM.

To start these services, use script xCP_Services.py.


Service | Code
----------|------------
XMS Agent | 32
BAM Server | 52
xPlore Search | 62
xPlore Index Agent | 72

