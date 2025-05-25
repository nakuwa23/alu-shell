# pwd
Prints or shows you the directory you're standing in.

# ls
Displays the contents of the current directory.

# cd ~
Changes the current working directory to the user's home directory.

# ls -l
Displays the contents of the current directory in long format.

# ls -la
Display current directory contents, including hidden files (starting with .)

# ls -lan
Displays the contents of the current directory in long format, includes hidden files, and shows numeric user and group IDs.

# mkdir /tmp/my_first_directory
Creates a directory named my_first_directory in the /tmp/ directory.

# mv /tmp/betty /tmp/my_first_directory/
Moves the file 'betty' from /tmp/ to /tmp/my_first_directory/

# rm /tmp/my_first_directory/betty
Deletes the file named betty in my_first_directory

# rmdir /tmp/my_first_directory
Deletes the directory my_first_directory that is in the /tmp directory.

# cd -
Changes the working directory to the previous one.

# ls -la . .. /boot
Lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

# file /tmp/iamafile
Prints the type of the file named iamafile, which will be in the /tmp directory when you run your script.

# ln -s /bin/ls __ls__
Creates a symbolic link to /bin/ls, named __ls__

# cp -u *.html ..
Copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

# mv [A-Z]* /tmp/u
Moves all files beginning with an uppercase letter to the directory /tmp/u.

# rm *~
Deletes all files in the current working directory that end with the character ~.

# mkdir -p welcome/to/school
Creates the directories welcome/, welcome/to/ and welcome/to/school at once, in the current directory.

