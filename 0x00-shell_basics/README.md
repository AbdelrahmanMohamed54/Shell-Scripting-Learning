pwd (print working directory)

ls (Display the contents list of your current directory.)

cd (changes the working directory to the user’s home directory)

ls -l (Display current directory contents in a long format)

ls -la (Display current directory contents, including hidden files (starting with .). Use the long format)

ls -aln Display current directory contents.Long format,with user and group IDs displayed numerically,And hidden files (starting with .)

mkdir /tmp/my_first_directory (creates a directory named my_first_directory in the /tmp/ directory.)

mv  (move or rename a file)

rm (remove a file)

rmdir / rm -r  (remove a directory)

cd - (changes the working directory to the previous one.)

ls -al . .. /boot (((lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.)

file /tmp/iamafile (prints the type of the file named iamafile)

ln -s /bin/ls __ls__ (Create a symbolic link to /bin/ls, named __ls__ )

cp -u ./*.html ../  (copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.)

mkdir welcome{,/to{,/school}} (creates the directories welcome/, welcome/to/ and welcome/to/school in the current directoryusing only 2 spaces.)

mv [[:upper:]]* /tmp/u/ (moves all files beginning with an uppercase letter to the directory /tmp/u.)

rm *~ (Create a script that deletes all files in the current working directory that end with the character ~.)

