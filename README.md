# Automate-backup-operations-in-ABC-International-INC-using-bash-scripts

**_Project Overview_**

ABC Secure Backup System
The ABC Secure Backup System is an automated solution designed to eliminate the bottleneck at ABC International INC. caused by the manual process of accessing and backing up encrypted password files. This system is tailored to enhance security, reduce human error, and save valuable time by automating the backup of updated encrypted files from core servers.


**Features**

What makes the ABC Secure Backup System unique?

Automated Backup: Automatically backs up all encrypted password files that have been updated in the last 24 hours.
Security Enhancement: Minimizes human interaction with sensitive files, reducing the risk of security breaches.
Error Reduction: Decreases the chances of human errors during the file backup process.
Efficiency Improvement: Frees up valuable intern hours, allowing them to focus on more critical tasks.


**_Technologies Used:_**

bash


**How to run the file backup.sh**:

First, download the project to your home device, then, you need to make the file backup.sh executable to do that:
open a terminal then run this command:

`chmod u+x backup.sh`

then to automate the process of backup you need to do the following:

Copy (don’t mv) the backup.sh script into the `/usr/local/bin/` directory, after that, `Using crontab` , schedule your `/usr/local/bin/backup.sh` script to backup the important-documents folder every 24 hours to the directory (/home/project).


**Acknowledgments:**

"Hands-on Introduction to Linux Commands and Shell Scripting" is the course that helped me a lot to do this project.
Thanks to IBM and Coursera for this great course.
