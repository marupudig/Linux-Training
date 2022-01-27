## Linux commands

`cd folder name` to open that folder path

`ls` This command is to list of files

`cd ..` is to create go back to the previous directory

`cd` Takes us to Home directory

`cd -` To go back to the previous directory
 
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

`pwd` present working directory - To see which directory we are 
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

`cd /var/log` To check all the application logs

`tail -f applicatiopn name` To check application logs

`wc` (word count) `wc -l filename` will help us count how many lines in that specific file `wc directoryname/*` to check directory words

`grep` (global regular expression print) To search a word in a specific file or directory. 

(eg:grep searchword filename)

(eg: grep -i searchword filename to find both upper and lower case)

(eg: grep -i searchword * which will find that word from all files)

(eg: grep -v searchwork filename/* to ignore the word)

To find a specific ip address or numbers we use grep '[0-9].[0-9].[0-9].[0-9]' filename/*

To find which line we have oure search word is we use -n

##VI Editor
`vi editor` vi filename to open the filename in editor(esc and i to get into insert mode)

(esc and u to undo)

(shift :wq/x(write and quit))

(esc and o to go to the next line with insert mode) 

esc and /searchword to search for a particular word in vi editor (after findings we type N(next) to look for other findings under same word)

esc and : %s(search)/wordname/replacingwordname/(to replace one word to another word for one place)%s(search)/wordname/replacingwordname/g(global) to replace all the words in that file.

esc and : line number To go to that specific line to edit that line

esc and 0: To move the cursor form last point to first

esc and Shift and A: To move the cursor from front to last

esc and dd: To delete the entire line

esc and 2 and dd: To delete both lines in a row

esc and shift+G - To go to end of the file (esc and gg to go to start of the file)

esc and shift+V and using down arrow we select the text and type d to delete those lines

esc and shift+V and using down arrows we select and type : (pattern will displays)/$(add something at the end of the line)/^(add something at the first of the line)/nameoftheword

esc and shift+v and using down arrows we select and the : (pattern displays) s/wordname/replacingwordname/g

`sed` (stream editor) To replace anything without opening file

(eg: sed 's/wordname/replacingwordname/g' filename) to permanent these changes we add -i next to sed.

`find` To find a specific file (eg: find . -name foldername)

(eg: find . -name '*filename*') if we don't know complete filename

(eg: find / -name "*filename*") To find specific file in the whole parent files.

(eg: find . -name "*filename*" -mtype f/d (file/directory) -mtime +10) To see last 10 days files

(eg: find directoryname -name "filename" -exec cat {} \;) to find and open that file.

(eg: find directoryname -name "filename" |xargs cat) to find and open that file.

(eg: find . -type d(directory)/f(files)) To display files or directory

(eg: find . -mtime/-mmin -1(find files/directories within a day or minutes))

(eg: find . -name filename -exec cp {} {}.$(backup) \;) To backup a file

`locate` 

`awk`

## Shell

`Ubuntu Kernal`It is a bridge between system and the user, it explains the command we give to the system. (Shell will be the interface between user and operating system). Kernal will be inside the operating system.

`Terminal` To execue a command we use terminals.

`cal` Which shows the calendar.

`date` displays date

`man` Manual (man cal to get help).

`lrt` list recursive timely manner




