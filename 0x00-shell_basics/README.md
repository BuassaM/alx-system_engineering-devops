
A script that prints the absolute path name of the current working directory

listit: Displays the contents list of your current directory.

-bring_me_home: Changes the working directory to the user’s home directory.

-listfiles: Displays current directory contents in a long format.

-listmorefiles: Displays current directory contents, including hidden files (starting with .).

-listfilesdigitonly: Displays current directory contents, using long format and also displays user and group IDs displayed numerically, and hidden files (starting with .).

-firstdirectory: Creates a directory named my_first_directory in the /tmp/ directory.

-movethatfile: Moves the file betty from /tmp/ to /tmp/my_first_directory.

-firstdelete: Deletes the file betty. The file betty is in /tmp/my_first_ directory.

-firstdirdeletion: Deletes the directory my_first_directory that is in the /tmp directory.

-lists: Lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

-file_type: Prints the type of the file named iamafile. The file iamafile will be in the /tmp directory.

-symbolic_link: Creates a symbolic link to /bin/ls, named __ls__. The symbolic link is created in the current working directory.

-copy_html: Copies all the HTML files from the current working directory to the parent of the working directory, but only copies files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory. All HTML files have the extension .html are considered.
