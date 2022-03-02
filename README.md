#Shell Scripting Basics

pwd === print working directory

ls === list directory contents

cd~ === bring me home

ls -l === list directory contents in long form

ls -la === list directory contents in long form including hidden files

ls -lan === list directory contents in long format,with user and group IDs displayed numerically  and  hidden files (starting with .)

mkdir /tmp/my_first_directory === Create a  directory inside the tmp directory

mv /tmp/betty /tmp/my_first_directory === Move file betty located inside the tmp directory, to my_first_directory inside the tmp directory.

rm /tmp/my_first_directory/betty === delete file betty.

rmdir /tmp/my_first_directory === delete the directory my_first_directory located in directory tmp.

cd - === Change directory to the previous one.

ls -al . .. /boot === lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

file /tmp/iamafile === Prints the type of file iamafile.

ln -s /bin/ls __ls__ === Create a symbolic link to /bin/ls, named __ls__

cp -u *.html ../ === copy all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

mv [[:upper:]]* /tmp/u === Move all files that begin with a capital letter to /tmp/u

rm *~ === Deletes all files in the current directory that end with a ~

mkdir -p welcome/to/school === Create directory welcome in current directory. Create directory to inside directory welcome. Create directory school inside directory to. The -p option creates any intermediate directories in the path argument.

ls -apm === List all files and directories of the current directory, separated by commas. Directory names should end with a (/).Files and directories starting with a dot (.) should be listed. The listing should be alpha ordered, except for dot (.) or dot dot (..), which should be listed at the beginning.

