Just a Nagios Forker
====================
Janf is a convenience utility meant to automate and simplify mundane and routine stuff involved with forking Nagios.

It will download latest master of Nagios Core and take care of removing all trademarks and renaming files as required which will make forking as easy as possible.

Usage
=====
Step 1) Download janf
Step 2) Choose a name for your fork
Step 3) Run janf to fork.

Example. To create a new project based ohm nohm monitor (or ohmnohmmon for short) based on Nagios you simply have to do the following:

    # download janf
    git clone https://github.com/palli/janf
    
    # Run janf to create a new project
    cd janf
    ./janf ohmnohmmon

Features to good to be true
===========================

If you believe any of these features are not present in janf I am happy to accept notifications in forms of pull requests that fix the problem.

  - Automatically create a github and sourceforge repo for your project
  - Tell you how many users have installed your fork
  - Register your project on freecode

Disclaimer
==========
In a perfect world there would be no need to fork to a good open source project. 

This program is useful in the unfortunate circumstance that you are forking a project for your own internal needs without
thinking about the good of a community.

This script does its best to keep all copyright notices unchanged. But in the end you are responsible for 
maintaining original copyright on your project. If ever in doubt, consult the commit messages in
the version control system.


