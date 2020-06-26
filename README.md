# simple-login-bash-script
a simple bash script that logs the time whenever the user reboots their system in a file and when the day is over archives the file in a tar archive to be stored.
Each day has an independant file. If a user boots the system more than once per day, the new time is appended to the file for that day. 
Can be automated with crontab on Linux

