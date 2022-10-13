# 0x02-shell_redirections
Learning objectives
# 1. A scripts that prints "Hello,World", followed by a new line to the standard output
     use the command # echo "Hello,World"
# 2. A script that displays a confused smiley "(Ôo)'
     use the command # echo "\"(Ôo)'"
# 3.A command to dislpay the content of the /etc/passwd file
    use the command # cat /etc/passwd
# 4.Display the contents of the two files /etc/passwd /etc/hosts
    use the command # cat /etc/passwd /etc/hosts
# 5.Display the last 10 lines of the file /etc/passwd
   use the command # tail -n 10 /etc/passwd
# 6.Display the first 10 lines of /etc/passwd
    use the command # head -n 10 /etc/passwd
# 7. Display the third line of the file iacta
    use the command # head -n 3 iacta | tail -n 1
# 8.A shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line
   use the command echo "Best School" >> \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) 
# 9.A script that write into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
   use the commnd # ls -la > ls_cwd_content
# 10.Write a script that duplicates the last line of the file iacta
    use the command # tail -n 1 iacta >> iacta
# 11.A script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
    use a comand # find ./ -type f -name '*.js' -delete
# 12.Don't just count your directories, make your directories count
     use the command # find . -type d ! -path . -print | wc -l
