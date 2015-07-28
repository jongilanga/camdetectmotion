# camdetectmotion
Protect your home with webcam that will auto detect motion under Ubuntu Linux

#Requirements

*Laptop running Ubuntu Linux or other Linux distro.
* Install motion ($sudo apt-get install motion).
* Configure motion to your needs using to config file (/etc/motion.conf).
* Create a local config dir ($sudo mkdir .motion)
* Copy the default config to your local file ($sudo cp /etc/motion/motion.conf ~/.motion
* Edit the config to your needs(make sure daemon is turn off it's on by default
* Run motion ($sudo motion)
* Watch videos on your localhost, http://localhost:8081


#Copy the files from local to your NAS/VHOST where you need to see them
* I run a cron for this and use rsync for this
