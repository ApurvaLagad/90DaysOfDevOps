# Day 6 Task: File Permissions and Access Control Lists

### Today is more on Reading, Learning and Implementing File permissions

 The concept of Linux File permission and ownership is important in Linux. 
 Here, we will be working on Linux permissions and ownership and will do tasks on
 both of them. 
 Let us start with the Permissions.

1) Create a simple file and do `ls -ltr` to see the details of the files [refer to Notes](https://github.com/LondheShubham153/90DaysOfDevOps/tree/master/2023/day6/notes)
 
 Each of the three permissions are assigned to three defined categories of users. The categories are:
-	   owner   —   The owner of the file or  application.
-	"chown" is used to change the ownership permission of a file or directory.
-	   group   —   The group that owns the file or application.
-	"chgrp" is used to change the gropu permission of a file or directory.
-	   others  —   All users with access to the system. (outised the users are in a group)
-	"chmod" is used to change the other users permissions of a file or directory.

    As a task, change the user permissions of the file and note the changes after `ls -ltr`

2) Write an article about File Permissions based on your understanding from the notes.
File permissions can be described as who, what, and which activities can be done to a file or directory.
who refers to users, groups, or others ;
what means to add, delete and set ;
which means read, write, and execute .
File permissions in Linux are used to control access to files and directories. Each file and directory has three sets of permissions: read (r), write (w), and execute (x). These permissions can be assigned to individual users, groups of users, and even everyone (represented as ‘others’). The permissions can be set using the chmod command, which takes a numeric code or symbolic notation to specify the desired permissions. For example, to give full access to a file, the command would be ‘chmod 777 file.txt’.

3) Read about ACL and try out the commands `getfacl` and `setfacl`
getfac1 : It can be used to determine which users and groups have access to a file or directory. It displays the mode, flags, owner, group, and other access control information associated with the file or directory

setfac1: It sets (replaces), modifies, or removes the access control list (ACL) to regular files and directories. It also updates and deletes ACL entries for each file and directory that was specified by path. If path was not specified, then file and directory names are read from standard input (stdin)

In case of any doubts, post it on [Discord Community](https://discord.gg/hs3Pmc5F)

Happy Learning
