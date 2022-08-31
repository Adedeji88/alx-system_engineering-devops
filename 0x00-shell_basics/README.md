ls is the command used to display the contents list of your current directory
cd ~ is the command that changes the working directory to the user’s home directory
ls -l is the command used to display current directory contents in a long format
ls -la is used to list the contents of current directory including hidden files in long format
ls -nal displays directory's contents in long format, with user and group IDs displayed numerically, and hidden files (starting with .)
mkdir /tmp/my_first_directory is used to create a directory named my_first_directory in /tmp directory
mv tmp/betty /tmp/my_first_directory is used to move the file betty from /tmp to /tmp/my_first_directory
rm /tmp/my_first_directory/betty is used to delete betty
rmdir /tmp/my_first_directory is used to delete the directory my_first_directory
cd - is used to change the working directory to the previous one
ls -la . .. /boot is used to list all files (even the ones wth names starting with a period character that are normally hidden) in the current directory and the parent of the working directory and /boot directory (in this order) in long format
file /tmp/iamafile prints the type of the file iamafile
ln -s /bin/ls __ls__ is used to create a symbolic link to /bin/ls named __ls__
cp -u */html .. is used to copy HTML files