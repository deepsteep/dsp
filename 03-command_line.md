# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

* show current working directory path : `pwd`
* creating a directory: `mkdir [insert directory name]`
* deleting a directory: `rmdir`
* creating a file using `touch` command: `touch "[insert file name]"`
* deleting a file: `rm [insert file name]`
* renaming a file: `mv [old file name] [new file name]`
* listing hidden files: `ls -a`
* copying a file from one directory to another: `cp [original file to be copied] [destination where new copy to be saved]`
---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`   

`ls` lists all files in the directory   
`ls -a` displays all files, including hidden files.  
`ls -l` displays files with long formatting.  
`ls -lh` displays files with human readable format.  
`ls -lah` displays all files, including hidden files, in human readable format.  
`ls -t` displays files sorted by last modified date & time, with newest first.  
`ls -Glp` displays, in color, long formatting, all files with a '/' at the end of directories.  

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:   

`ls -d` displays only directories.  
`ls -R` displays subdirectories as well.  
`ls -t` displays files sorted by last modified date & time, with newest first.  
`ls -1` displays each entry on a line.  
`ls -m` displays entries as comma-separated list.  

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

`xargs` takes data from standard input and executes the command.

xargs find -name   
"*.txt"

This finds file names in the current directory that contains "*.txt"
 

