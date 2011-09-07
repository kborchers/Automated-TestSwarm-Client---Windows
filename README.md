Automated Test Swarm Client - Windows
================================
This is a small project to setup a batch file to automate the startup of all local browsers on a Windows machine and then set the machine to restart after 4 hours.

There is some machine configuration that needs to take place in order to use this script.
>1. All of the browser home pages need to be set to the TestSwarm user page so that the tests start running immediately. For example, http://swarm.jquery.org/user/kborchers/.
>2. Depending on your setup, you may need to add paths to the browser executables parent folder, to the PATH environment variable. I had to add the path to Opera but all of the others worked without additional config.
>3. The batch file needs to be placed in the Startup folder so that it runs when the machine starts and is run everyt time the script reboots the machine