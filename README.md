The HARCON (Home Automation Remote CONtrol) is a project to provide
full control of home automation from the internet using a RESTful API
set. The architecture is based on Service Oriented Architecture with
splitted backend and frontend The backend is implemented in Python,
running on a Linux OS, while the frontend is a single web page
application written in HTML5/Javascript and using AngularJS as the
Javascript MVC framework.  The APIs implemented in the backend engine
provide the capability to remotely control the execution of scheduled
tasks (generated in bash shell) that execute digital I/O commands
using the standard proven and reliable 'cron' and 'at' daemons.
