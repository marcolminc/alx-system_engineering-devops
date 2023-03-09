The readme describing what each script in this folder is doing:
0. 0-current working directory prints the absolute path name of the current working directory.
1. 1-listit displays the contents list of your current directory.
2. 2-bring me home changes the working directory to the user's home directory.
3. 3-listfiles displays current directory contents in a long format.
4. 4-listmorefiles display current contents, including hidden files (starting with .) in long format.
5. 5-listfilesdigitonly displays current directory contents in long format and numerically (user and group IDs).
6. 6-firstdirectory creates a directory named my_first_directory in the /tmp directory.
7. 7-movethatfile moves the file betty from /tmp to /tmp/my_first_directory
8. 8-firstdelete deletes the file betty in /tmp/my_first_directory
9. 9-firstdirdeletion deletes the directory my_first_directory that is in the /tmp directory
10. 10-back changes the working directory to the previous one.
11. 11-lists lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
12. 12-file_type prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when the scripts are run by the checker.
13. 13-symbolic_link creates a symbolic link to /bin/ls, named __ls__. which is created in the current directory.
14. 14-copy_html copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
