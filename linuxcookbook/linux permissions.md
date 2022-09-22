
# permissions.
   
  how we know the permission of files:

  ls -l filename.

  permissions are divided into 3 parts :
  admin   
  group
  public

 permissions are of 3 types :
 r  : read 
 w : write 
 x : executable
-: permission not set
 
permissions are divided into 3 numbers:
1  execute  (to run)
2  write
4  read

example : if we want to  give permissions by our self we do this:
 suppose we have a file namely ' index ' which has all the permissions read write and execute permission for public and we want that the public can only read and write that file here is what we do ;

2+4 = 6  because 2 is for write and 4 is for read .

and here is how we give it in terminal :

chmod  filename 6       and hit enter

chmod index 6              and hit enter
  
[this is how i did it ! click on this link ](https://drive.google.com/file/d/1YofUDM3peKqm9HQKXR6fJxIzEaVw4ocr/view?usp=sharing)

