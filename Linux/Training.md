## Linux commands

`cd folder name` to open that folder path

`ls` This command is to list of files

`cd ..` is to create go back to the previous folder
 
`mkdir` To create a new directory 

`cat`To open the file completely

`cat >> filename.txt`-To create file and enter data at the same time (after entering to exit we hit ctrl+c)

`touch filename.txt` to create a new file

`touch filename{1..5}` To create multiple files at once.

`vi filename` To create a file as well

`less` To open the file step by step by entering [to exit we click esc and typ :q enter]

`cp` is to copy/backup from one file to another. (only in local command) (eg: cp old file name space new backup file name)

`mv` it will move/edit all the data to a new file name.

`date +%d-%m-%y-%H:%M:%S` (giving the format for a date)

`cp` old file name and backup file name.$(date +%d-%m-%y-%H:%M:%S)- to have the file name saved with date format

`Stat` it gives detail information of a file

`ls-la` to see hidden files and normal files inside directory

`touch .filename` having . before filename will hide that file.

`rm filename` to delete a text file

`rm -rf(recursive force) directory name` To delete a directory

`ls -lrt`list the files in sorting manner.
## Permissions
`permissions` rwx(read write execute)r(user)-4,w(group)-2,x(other)-1

`id` To check which user we are on with all details of that user.

`whoami` to check which user we are using.

`w/who` details list of when we logged in. 

`chmod 777 filename` to change file permissions

default file permissions 644.

`chown` (to change permissions for an user) eg: chown username:groupname filename. 

`sudo` To check what permissions we have

`sudoers` to give permissions to change user access for rwx (/etc/sudoers)

`top/top -c` What applications are running in the server we logged in (type c to know what files it is using)

`df -h`to check disk free space

`du -h */systemname` To check disk usage (* to see all system usages)
 
`elastic block storage (aws)` additional service to create new instance with storage which will be permanent. 

`ephemeral storage` default storage (it is linked with the system, we terminate/restart storage terminates as well) (to know these type of storage it will show the file name as xvd) 

## Shell

`Ubuntu Kernal`It is a bridge between system and the user, it explains the command we give to the system. (Shell will be the interface between user and operating system). Kernal will be inside the operating system.

`Terminal` To execue a command we use terminals.

`cal` Which shows the calendar

`date` displays date

`man` Manual (man cal to get help).

`lrt` list recursive timely manner




