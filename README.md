# vzp-i3-configs
Contains my i3 configs and setup scripts

So, working on updating to 4.10.2 on Kali and on straight debian so thought I would put my 
configurations, steps, dependency stuff here.

Used to have to temporarily add jessie sources to /etc/apt/sources.list but no longer thanks to recent updates by Debian.

Hopefully this is useful to others, lessons any pain, etc.

You can manually follow the steps in 'steps'
** or **
copy script-install.sh to your system.
script-install.sh is meant to be run as a user that has sudo permission.
it will clone this repo and the i3 repo, 
sudo apt-get -y install all dependencies
sudo make and sudo make install
sudo apt-get -y install some helpful applications
copy the config files to the user directory and to the /root/ directory and you are done!
