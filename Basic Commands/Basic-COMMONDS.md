# Hack-With-TERMUX
# List of all the termux basic commands:
-  You can run this command in a sequence to practice and know your self how these commands work on 
termux.if you have any questions or ideas please comment I will be happy to help you.
-  SOURCE SITE : www.LearnTermux.tech
## Update all the packages and dependencies installed on the system:
 $ apt update && apt upgrade
-  If any update is available it will ask you on the terminal if you want to upgrade or not, press Y if 
you want the update.
## Grant storage permission:
 $ termux-setup-storage
-  now you can access your Storage and all the folder in it using termux.
## Know Which directory you are in:
 $ pwd
-  This command will tell you, your present working directory
## List all the files and directories:
 $ ls
-  this command will show you the folder and files in your current working directory.
## Move forward in directories:
 $ cd storage
-  cd command allows you to move in a folder just type cd and the folder name you wanna move 
here I am moving in storage.
## Move backward in directories:
 $ cd ..
 -  by typing cd ..(between cd and .. we have to put space) you will go back in the directory you 
were in.
## Clear Screen:
 $ clear
-  by typing clear in the termux you can clear all the previous results.
## Create a folder or a directory:
 $ mkdir folderName
-  Mkdir Stand for make directory. Type mkdir and give a space and type folder name and press 
enter to see the folder you have just created just type ls.
## Delete a folder or a directory:
 $ rmdir folderName
-  Rmdir stands for Remove Directory.Type rmdir space folder name to remove that folder.
## Delete Non-Empty directory or folder in termux:
 $ rm -rf folderName
-  Please use this command with caution.This command will remove a folder and all the files and 
folders within it.This command is useful when you want to delete any project downloaded from 
Github.
## Copy a file from one directory to another directory:
 $ cp files-name file-path
-  You can copy files by typing cp the file name and after giving a space you can type the path 
where you wanna copy the file E.g: cp virus.apk /storage/shared this will copy the virus.apk to 
the storage/shared folder.
## Search for the specific package in termux:
 $ pkg search package-name
-  It will show you all the package related to that package name.
## List all the available packages in termux:
 $ pkg list-all
-  it will show you all the packages that are available in the APT repository of termux.
## Install a Package:
 $ pkg install packageName
-  you can install any package from the list, just type pkg install package-name.
## Uninstall a Package:
 $ pkg uninstall packageName
-  you can uninstall any package from the list, just type pkg uninstall package-name.it will ask you 
where if you wanna delete the package or not press y and the package will be uninstalled.
## Install Python in termux:
 $ pkg install python
-  Just type this command and it will be installed in your termux press y if it asks for 
confirmation.after installing python you can write code and also run your own python scripts. 
Type python to check if python is properly installed or not.
## Install Git in termux:
 $ pkg install git
-  Git will allow you to download any project from the github.
## Download projects from GitHub repository :
 $ git clone Link-of-the-project
-  If you want to download any project from the git hub you can just use the above just change the 
Link-of-the-project with your link
e.g: git clone https://github.com/adi1090x/termux-style.git
## Check all the running processes in termux:
 $ top
-  This command will show you all the tasks running on your termux. To quit the top command on 
termux just press CTRL+C on your keyboard.
## Create a text file in termux:
1. first, you have to download a package name nano. Type on termux pkg install nano press y when 
asking for confirmation.
2. type nano on the terminal.
3. type anything you want I am typing hello world.
4. Press CTRL+X and press Y to save the file.
5. Give the file name anyname.txt and press enter.
6. Type ls command to see your directory.
## See what's inside a text file:
 $ cat file-name
-  Run this command and everything in the text file will be printed on the terminal.
e.g: cat data.txt
## Delete a file in termux:
 $ rm file-name
-  To delete any file within the directory in, just type the rm name of your file and press enter and 
it will be deleted.
e.g: rm data.txt
## List all the installed Packages in termux:
 $ dpkg --list
-  By Using this command You will be able to see all the installed packages in your termux app.
Thanks for reading.

