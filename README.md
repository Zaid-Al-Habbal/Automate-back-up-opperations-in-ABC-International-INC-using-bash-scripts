# Automate-backup-operations-in-ABC-International-INC-using-bash-scripts

Welcome to the "Automate backup operations in ABC International INC using bash" repository.

**The Problem that my project would solve**:

You are a lead Linux developer at the top tech company “ABC International INC.” ABC currently suffers from a huge bottleneck - each day, interns must painstakingly access encrypted password files on core servers, and back up those updated within the last 24 hours. This introduces human error, lowers security, and takes unreasonable work.

As ABC INC’s most trusted Linux developer, you have been tasked with creating a script backup.sh which automatically backs up any files that have been updated within the past 24 hours.

**_Technologies Used:_**

bash

**How to run the file backup.sh**

First, download the project to your home device, then, you need to make the file backup.sh executable to do that:
open a terminal then run this command:

`chmod u+x backup.sh`

then to automate the process of backup you need to do the following:

Copy (don’t mv) the backup.sh script into the `/usr/local/bin/` directory, after that, `Using crontab` , schedule your `/usr/local/bin/backup.sh` script to backup the important-documents folder every 24 hours to the directory (/home/project).

**Acknowledgments:**

"Hands-on Introduction to Linux Commands and Shell Scripting" is the course that helped me a lot to do this project.
Thanks to IBM and Coursera for this great course.
