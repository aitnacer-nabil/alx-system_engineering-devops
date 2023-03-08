0-current_working_directory : a script that prints the absolute path name of the current working directory
1-listit : Display the contents list of your current directory.
2-bring_me_home:changes the current working directory to the home directory (cd ~). but to run script u should use source or  .
3-listfiles: Display current directory contents in a long format
4-listmorefiles : ls -la .. -Display current directory contents, including hidden files (starting with .). Use the long format.
5-listfilesdigitonly :ls -lan The options used here are:-l: display in long format -a: show hidden files -n: display user and group IDs numerically
6-firstdirectory :  a script that creates a directory named my_first_directory in the /tmp/ directory.
7-movethatfile : Move the file betty from /tmp/ to /tmp/my_first_directory.
8-firstdelete : delete file using rm -rf filename
9-firstdirdeletion : delete directory
10-back : a script that changes the working directory to the previous one.
11-lists :  a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format. (ls -la . .. /boot)
12-file_type :  a script that prints the type of the file named iamafile
13-symbolic_link : the ln command to create a symbolic link (-s option) to /bin/ls, with the link name __ls__.
14-copy_html :  a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
100-lets_move :  a script that moves all files beginning with an uppercase letter to the directory /tmp/u.
101-clean_emacs :  a script that deletes all files in the current working directory that end with the character ~
102-tree : create atree folder
103-commas :ls -ap: lists all files and directories in the current directory, including hidden files and directories, and adds a slash at the end of directory names.
grep -v '/\.\{1,2\}$': filters out the directories . and .., which end with one or two dots, by using grep with the -v option to invert the match, and the regular expression /\.\{1,2\}$ to match directories that end with one or two dots.
sort -Vf: sorts the remaining files and directories alphabetically, except for . and .., by using sort with the -V option to sort version numbers first, and the -f option to ignore case.
tr '\n' ',': replaces newlines with commas.
echo: appends a newline at the end of the listing.
