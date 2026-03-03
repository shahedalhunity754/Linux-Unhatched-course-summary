# My Linux Cheat Sheet 🐧
# NGD Linux Unhatched
 
 Command   | Description                         | Example 
 
-`cd`       | change directory                    | cd Documents 
-`whoami`    |to show the name of the current user | ---
-`ls`        |list                                 | ls documents 
_________________________________________________________________________________________________________________
sysadmin@localhost:~$ 
-sysadmin : name of the user 
-localhost: name of the device 
_________________________________________________________________________________________________________________
  Option    | Description 
 -v         | verbose flag : adding more "v" increases  the level of detail ;this is useful when trying to solve 
              a cloud server problem.
 -1         | makes the list vertical 
 pwd        | print working directory : discover the current location within the file  system.
 ..         | parent directory : taking a step back 
 .          | current directory 
 ~          | home directory 
 _______________________________________________________________________________________________________________
how Linux read the properity of  certian file / directory :
**the first letter**
d         | directory 
-         | regular file 
l         | Symbolic link(it should put an arrow showing the original path)
s/p       | sockets & pipes (to communicate insidde the program )
b/c       | hardisk 
**the other letters**
*first 3 letters* : owner 
*second 3 letters* : group 
*third 3 letters* : others 
______________________________________________________________________________________________________________
r : read
w: write
x: execute
**we can't make a file with  -rwxrwxrwx becuase it means everyone can delete it**

we will use this file as example : 
     drwxr-xr-x   2 root    root     4096  Apr 11    2014   upstart  
   d :type of file 
rwxr-xr-x  : permissions
2 : hard link count 
root : user owner 
root  : group owner 
4096 : file size  
Apr 11    2014 :modification date
upstart :name of file 

-by default ,Linux displays files alphabetically by name, and via the option *-t*, it will display files by modification time from newest to oldest. 
-option *-S* display the files by file size.
-we use option -r to reverse. if you put it alone with *ls*, it will give me the filenames from Z to A.And if I write *-ltr*, it will write them in details and sorted from oldest to newest. 
-when I want to quickly specify the the current folder, I put fullstop (.).
______________________________________________________________________________________________________________



https://www.linkedin.com/posts/shahed-al-hunity-5a452b327_i-successfully-completed-an-introductory-activity-7429905651860066304-h0zX?utm_source=share&utm_medium=member_android&rcm=ACoAAFJ7W4wB1iN9yPOyKdjlVBZtEiNDLjAaGW4
