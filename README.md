# PSUControl-Scripts
Scripts for Octoprint PSUControl Plugin

## Installing the scripts
* Edit the scripts and change PSUPIN=14 at the top to your relay GPIO pin number.
* Upload the psu_ scripts to the Octopi /usr/local/bin directory.
* Change file permissions by running the command:  `sudo chmod 755 /usr/local/bin/psu_*`
* Run psu_setup at boot time. Edit /etc/rc.local and add the line `/usr/local/bin/gpiosetup` near the top of the file.
* Configure PSU Control to use the scripts as shown in PSUControl Setup.png.
* Reboot OctoPrint
