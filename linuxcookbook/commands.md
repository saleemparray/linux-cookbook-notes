                     commands    ----           uses

     ls             ---------    is used to list files or directories
     
     history        ---------  used to view the previously executed command.

     cp             ---------     used to copy file from one directory to another.
     
     mv            ---------- (i) It renames a file or folder. (ii)  It moves a group of files to a different directory.
     
     /    ----------- root directory
     
     locate    -------     is used to find the files by name.
     
     find ------- is used to find the file by name.
     
     cat ------- to read the data inside in the file.
     
     zip -------   is used to compress the files to reduce file size and also used as file package utility.
     
     unzip ------- -   to Extract all files from current folder.
     
     head ----- The head command reads the first ten lines of a any given file name. command:  head [options] [file(s)].
     
     tail -------- The tail command allows you to display last ten lines of any text file.
     
     sort -------- used to sort a file, arranging the records in a particular order
     
     alias ------ is used to create short cuts for the commands in linux.
     
     cd -------   is used to change current working directory.
     
     rm ------   is used to remove objects such as files, directories, symbolic links and so on from the file system.
     
     mv -------  is used to move one or more files or directories from one place to another.
     
     touch -----  is used to create, change and modify timestamps of a file.
     
     wc -----  it is mainly used for counting purpose.
     
     pipes ' | ' -----  Pipe is used to combine two or more commands.


   ## Detailed :
   
 ##   ls:  
 
      ls -l   ::  shows file or directory, size, modified date and time, file or folder name and owner of the file, and its permission.
      
      ls -a   ::  List all files including hidden files starting with ".".
      
      ls -lh  ::  shows size that humans can easily understand.
      
      ls -F   ::  add the "/" character at the end of each directory.
      
      ls -r   ::  display files and directories in reverse order.
      
      ls -R   ::  
      
      ls -lS  :: displays file size in order, will display big in size first.
      

## history :

       history -c  ::  to remove whole history.
       
       history | tail :: to view last 10 commands.


##  find  :

 how to find : 
 
    $ find [where to start searching from]
    [expression determines what to find] [-options] [what to find]

    eg:  find ./GFG -name sample.txt

 **How to find and delete a file with confirmation.**
 
    find ./GFG -name sample.txt -exec rm -i {} \;
            
**Search for empty files and directories.**

    find ./GFG -empty
    
**Search text within multiple files.**

    find ./ -type f -name "*.txt" -exec grep 'Geek'  {} \;


## cat :

**To view multiple files Command:**

    cat file1 file2
    
**To view contents of a file preceding with line numbers Command:**

    cat -n filename

**Create a file Command:**

    cat > newfile     (not runned but trying)

**Copy the contents of one file to another file.**

    cat [filename-whose-contents-is-to-be-copied] > [destination-filename]
