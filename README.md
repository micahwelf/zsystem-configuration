# zsystem-configuration

This is a simple collection of system configuration scripts, apps, and settings, designed to use in new system installations and system recovery.  This is NOT for a System Z architechture; It is named Z system as a shorthand way of saying a Z Shell-centered system (/bin/sh is Zsh instead of dash or bash, and most of the system is integrated with Zsh functions, etc.).  Most of the system specifics will favor an Arch Linux with System-D configuration, since their package management system is the easiest and most compatible with this kind of customization.

This is private, but doesn't need to be secured, since nothing unsecure is supposed to go here.  scripts should be:
* gather: get files from system, like backup
* deploy: Apply files to system without prompting
* apply:  Apply files to system with prompting                                                                                                                                                                                                                                                                                     
