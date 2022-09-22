
# commands 
Note : directory is folder simply.

#### df commands
is used to display information related to file systems about total space and available space.

df :  allover shows information about file system
df -h :  human readable
df -h -BG  : shows size in Gigabytes.
df -h -BK   :  shows size in Kilobytes.
and so on .

#### du commands:
The du command can be used to track the files and directories which are consuming excessive amount of space on hard disk drive.

du : shows us file usage of all files 
du -h :  human readable.
du -h file directory : shows us space used by that directory.
du -ah file directory : shows us space used by file inside that directory.
du -ahc file directory : shows us the total space used by that directory at the end . 

#### free commands:
Note : shows us information about ram not hard disk.

free -h : shows us all used and free space of ram.
free -h -s second : it will refresh in the given seconds and give us the information about memory.
free -h -c number : it will run the command in given number in every second and shows us information of ram.


