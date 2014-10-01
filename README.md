cleantag4nautilus
=================

Cleantag4nautilus is a bash script which is used to rename music files massively.




DESCRIPTION
====================================================================
Normalize with one click all your music files names to new and clean name without weird words, i.e. information about the download web.
For the time being, it is used for mp3, wma and m4a files.




REQUERIMENTS
====================================================================
This program is bash script, therefore it can work in Linux and other Unix OS based.
Nautilus, and zenity packages are also requeriments.
This script works without any installation in Ubuntu, and other OS GNU/Linux with Nautilus or Nemo file browser.




INSTALATION
====================================================================
Ubuntu 13.04 and later versions include nautilus-actions by default, for previous versions:

$ sudo apt-get install nautilus-actions



Step 1:
Download the script in some folder. I.e: /home/$USER/scripts/cleantag4nautilus/


Step 2:
Give the permission to execute the script
$ chmod +x /home/$USER/scripts/cleantag4nautilus/cleantag4nautilus


Step 3:
Open nautilus-actions-config-tool


Step 4:
Define new action and rename new action to cleantag4nautilus


Step 5:
In Command tab enter:
Path: /home/$USER/scripts/cleantag4nautilus/cleantag4nautilus
Parameters: %f


Step 6:
In Command tab edit basename filter * to *.mp3



USE
====================================================================
Right click over the mp3 file, select Nautilus-Actions actions, and select cleantag4nautilus. Enjoy it!!




