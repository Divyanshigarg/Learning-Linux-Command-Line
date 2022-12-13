# Chapter Quiz: Files,Directories and Permissions
1. Which command shows a long listing, including file sizes and ownership information?

        a. ls -l

        b. ls -A

        c. ls -d

        d. ls -a
```
Correct: a
The -l option tells ls to provide a long listing.
```
2. If a file path has a space in it, you can wrap the path in quotes, or you can _____ the space with a \ character.

        a. ignore

        b. escape

        c. highlight

        d. skip
```
Correct: b
Escaping a character tells the shell to interpret it literally, rather than as part of a command.
```
3. What does the mkdir command do?

        a. marks a directory for deletion

        b. removes a directory

        c. moves a directory

        d. creates a directory
```
Correct: d
mkdir will create a specified directory, and mkdir -p will create parent directories as necessary for a deeper path.
```
4. The rmdir command _____.

        a. can delete a whole tree of directories

        b. can delete a directory and its contents

        c. can only delete an empty directory

        d. deletes directories, but not files, in a tree of directories
```
Correct: c
While the rmdir command can only delete empty directories,you can use rm -rf to delete
non-empty directories and trees of directories.
```
5. What could you write to rename the file report.txt to output.txt?

        a. mv output.txt report.txt

        b. mv report.txt

        c. rm report.txt output.txt

        d. mv report.txt output.txt
```
Correct:d 
While mv is usually used to move files, we can also use it to rename them.
```
6. What can you write to delete a directory called Photos which contains many subdirectories?

        a. rm -r Photos

        b. rm -f Photos

        c. rm Photos

        d. rmdir Photos
```
Correct: a
The -r option tells rm to remove the file hierarchy, not just files.
```
7. The find command lets us look for files by name, size, etc., _____.

        a. only in the user's home directory

        b. in all directories on the system regardless of permission

        c. wherever the user who runs it has permission to view

        d. only in system directories, not in user directories
```
Correct: c
When we run a command, it has the same access that the user running it does.
```
8. You want to make a copy of the poems.txt file. Which command would you use?

        a. del poems.txt poems2.txt

        b. mkdir poems.txt

        c. cp poems.txt poems2.txt

        d. rm poems.txt
```
Correct: c
This command will create a copy of poems.txt called poems2.txt.
```
9. Why would a normal user not do any harm by trying to change system files and directories?

        a. Normal users would not know how to access these files and directories.

        b. Normal users cannot see system-level files and directories.

        c. Normal users can actually do significant harm to the computer by altering these files and directories.

        d. Normal users do not have sufficient permissions to modify these files and directories.
```
Correct: d
This statement is correct, and normal users would need root or sudo authority to change these files and directories.
```
10. While all other users' home directories are kept in /home/, the superuser's home directory is stored at _____.

        a. /sudo

        b. /home/root

        c. /home

        d. /root
```
Correct: d
Root is a special user, and it has a special home directory.
```
11. Which of these is an absolute path?

        a. /var/lib/mysql

        b. var/lib/mysql

        c. ../Documents

        d. ../../mysql
```
Correct: a
We can tell this is an absolute path because it begins with the slash that represents the filesystem root.
```
12. In most shells, what is the significance of the ~ character?

        a. It represents the parent directory of the current working directory.

        b. It indicates that the shell is processing data and should not be interrupted.

        c. It represents the path to the current user's home directory.

        d. It represents the filesystem root.
```
Correct: c
Using tilde expansion, most shells use this character to represent the home directory of the current user.
```
13. If your current working directory is /home/alice/Documents/Financial, and you want to change it to /home/alice, you can use the command _____.

        a. cd /alice

        b. cd ../../

        c. cd ../alice

        d. cd ..
```
Correct: b
This command uses relative path indicators. Two dots (..) represents the parent directory of any given directory.
```
14. What command allows you to change to another directory?

        a. cd

        b. rm

        c. ls

        d. mv
```
Correct: a
This command will change to a specified directory or, without any arguments, will change the working directory 
to the user's home directory.
```
15. You have come across an unknown file named myfile.txt. Which command would you type to display ownership or modification information about this file?

        a. ls myfile.txt

        b. stat myfile.txt

        c. file myfile.txt

        d. cat myfile.txt
```
Correct: b
This command will display ownership and modification information, as well as other details about the file.
```
16. What can you write to find files in Alice's home directory with report in the name?

        a. find /home/alice -name "report"

        b. find /home/alice -name "*report*"

        c. find -name "report" /home/alice

        d. find -name /home/alice "report"
```
Correct: b
The find command's syntax is a little bit different from most other commands.
```
17. A symbolic link using a relative path will break if _____.

        a. the link is moved, but not the referenced file

        b. the referenced file is moved, but not the link

        c. it's impossible to break a symbolic link

        d. the link or the referenced file is moved
```
Correct: d
If you want to make a link that can be moved without breaking, use an absolute path or a hard link.
```
18. What does the command ln -s outcome.txt report.txt create?

        a. A hard link named outcome.txt that refers to report.txt.

        b. A symlink named report.txt that refers to outcome.txt.

        c. A hard link named report.txt that refers to outcome.txt.

        d. A symlink named outcome.txt that refers to report.txt.
```
Correct: b
Remember that a symbolic link will break if the original file is moved.
```
19. You have downloaded a program from the web, and when you try to run it, you receive the error:

-bash: ./newprogram: Permission denied

How would you attempt to resolve this problem?

        a. There is nothing to be done, the program is simply broken.

        b. Run the command chmod u-x newprogram to add execute permissions to the file.

        c. Run the command chmod 644 newprogram to add execute permissions to the file.

        d. Run the command chmod u+x newprogram to add execute permissions to the file.
```
Correct: d
```
20. You need to use superuser privileges to _____.

        a. create files in our own home directory

        b. log into the system

        c. allow other users to access our files

        d. modify system settings and software
```
Correct: d
Changes to the system need to be done by a user with elevated privileges.
```
21. You want to find any files that start with Po and end with e. Which character would you insert between o and e to match any number of every possible character?

a. /

b. *

c. .

d. @
```
Correct: b
This character is a wild card and will match any number of any characters in a filename, for example, Poe, Pole, and Police.
```
22. File permissions let us control who can _____.

        a. delete files only

        b. create files only

        c. read, write, and execute a file

        d. change how files are executed only
```
Correct: c
R, W, and X are the fundamental categories of access for the user, group, and others.
```
23. If you we want to execute using superuser privileges, what command do you use in front of another command?

        a. bash

        b. sudo

        c. root

        d. admin
```
Correct: b
This command can be thought of as 'switch user and do', 'superuser do', or 'substitute user and do', depending on who you ask.
```
24. How would you alter this command using octal notation to give read, write, and execute permissions to the file's owner, members of the file's designated group, and all other users for the file poems.txt?
chmod poems.txt

        a. chmod 777 poems.txt

        b. chown poems.txt

        c. chmod u-r poems.txt

        d. chmod 244 poems.txt
```
Correct: a
This changes the permissions for the poems.txt file, and gives read, write, and execute permissions to the file's owner, members of the file's designated group, and all other users.
```
25. File permissions can be set using two modes. What are they?

        a. octal and symbolic

        b. octal and decimal

        c. representative and symbolic

        d. normal and administrative
```
Correct: a
Depending on how you need to change the permissions of a file, it can be easier to use one or the other.
```
26. What is the highest level of the filesystem hierarchy called?

        a. home

        b. level 0

        c. root

        d. C:
```
Correct: c
The filesystem root, represented by /, is the highest level of the filesystem hierarchy -- everything else in the filesystem is nested somewhere within the root filesystem.
```
