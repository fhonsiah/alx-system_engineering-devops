# Shell basics
1. Getting the absolute path name of the current working directory
   use the command # pwd
2. Display the content list of your current directory
   use the command # ls
3. A script thaat changes the working directory to the user's home directory
   use the command  # cd
4. Display current directory contents in a long format
   use the command # ls -l
5. Display current directory contents,including hidden files(starting with .)
   use the command # ls -la
6. Create a script that creates a directory named my_first_directory in the /tmp/ directory
   use the command # mkdir /tmp/my_first_directory
7. create a scripts that moves a file from one directory into another directory
   use the command # mv  /dirA  /dirB/
8. Delete the file in a certain directory
   use the command # rm /tmp/my_first_directory/betty
9. Delete a directory inside another directory
   use the command # rmdir /tmp/my_first_directory
10. A script that changes the working directory into the previous one
   use the command # cd -
11. A script that list all files (even the hidden ones beggining with a period character,paretnt of the working directory & the /boot directory
    use the command # ls -la . .. /boot
12. A script that prints the type of file iamafile that is located in the directory /tmp
    use the command # file /tmp/iamafile
13. Create a symbolic link to /bin/ls named __ls__
    use the command # ln -s /bin/ls __ls__
14. A script that copies all the html files from one directory to another,but only copy files that do not exist in the parent directory
    use the command # cp -i *.html ..
15. A script that moves all files beggining with uppercase letters to the directory /tmp/u
    use the command # mv [[ upper ]]* /tmp/u
16. A script that delete all files in the current working directory that end with the character ~.
    use the command # rm *~ 
17. A script that creates several directories welcome,to and school.
    use  the command # mkdir /welcome/to/school
