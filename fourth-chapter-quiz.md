# Chapter Quiz: Common Command Line Task and Tools

1. What does the command tar -cf docs.tar Documents/ do?

            a. It creates a compressed archive of the Documents directory, called docs.tar.

            b. It extracts an archive named docs.tar into a directory called Documents.

            c. It creates an archive of the Documents directory, called docs.tar, with no compression.

            d. It creates an archive of the Documents directory and outputs its contents to the standard output.
 ```
Correct: c
The c option creates an archive, and f outputs it to a file instead of the standard output.
```
2. Many command-line tools are intended to be used in pipelines with other commands because they are _____.

            a. complicated

            b. modular

            c. large

            d. old
```
Correct: b
```
3. To extract files from a tar file, use the option _____.

            a. d

            b. u

            c. x

            d. z
```
Correct: c
This option will tell tar to retrieve files from an archive.
```
4. What symbol is often used to redirect the standard output or standard error into a file or other location?

            a. %

            b. $

            c. <

            d. >
```
Correct: d
The redirection operator can also be used to truncate a file.
```
5. Which character represents a UNIX pipe?

            a. |

            b. /

            c. #

            d. &
```
Correct: a
This character isn't widely used, so it can be odd to work with at first.
```
6. What purpose do zip files serve in Linux?

            a. They allow us to combine files in a space-saving way, and are commonly used when we exchange files with other 
            platforms or across the internet.

            b. They combine many files into one file, but do not offer benefits such as reduced size.

            c. They increase the size of files, taking up more space.

            d. They are a Linux-only method of combining and compressing files.
```
Correct: a
Zip files allow us to reduce the space taken by one or more files, and provide a cross-platform file that we can exchange easily.
```
7. How can the UNIX Philosophy be summed up?

            a. The older the computer, the better it runs.

            b. Text is always better than graphics.

            c. Tools should do one thing well, and communicate with each other using text.

            d. Open source forever!
```
Correct: c
We leave it up to the user to combine tools in a way they need to.
```
8. You redirect output to a specific file but when you open it, you find the file is missing its original contents. Why are the original contents gone?

            a. You used two > signs, which overwrites the contents of the file.

            b. You cannot redirect to a file without overwriting the current contents of the file.

            c. Your command hid the original contents of the file, and they can be accessed by typing ls -A.

            d. You used a single > sign, which overwrites the contents of the file.
```
Correct: d
A single > when redirecting file contents will overwrite the contents of the target file.
```
9. To view only the first eight lines of the file report.txt, you could write _____.

            a. head -n8 report.txt

            b. head report.txt,8

            c. head 8 report.txt

            d. head report.txt -8
```
Correct: a
The -n option sets what number of lines to display.
```
10. Input and output streams are numbered. Which of these represents the standard error?

            a. 2

            b. 4

            c. 1

            d. 0
```
Correct: a
0 is the standard input, and 1 is the standard output.
```
11. What does a pipe do?

            a. It stops information from flowing between commands.

            b. It discards the output of a command and starts the next command with a blank slate.

            c. It works only when connected to the internet.

            d. It sends the output of one command to the input of another.
```
Correct: d
Pipes allow us to connect simple tools together in complex ways.
```
12. A user wants to view the contents of the file poems.txt. Which command would be used to see the entire contents of this file?

            a. view

            b. head

            c. tail

            d. cat
```
Correct: d
This command will display all contents of the file selected.
```
13. To set environment variables that persist between bash sessions, you can edit _____.

            a. ~/.bash_profile

            b. ~/env

            c. ~/bash

            d. /profile
```
Correct: a
The .bash_profile file can set many other parameters for your bash session as well.
```
14. Which command lets you scroll around and search in a text file?

            a. cat

            b. tail

            c. less

            d. head
```
Correct: c
The less command provides a minimal interface within which we can move around a file.
```
15. Vim has two primary operating modes. What are they?

            a. command mode and insert mode

            b. command mode and control mode

            c. control mode and text mode

            d. text mode and graphics mode
```
Correct: a
Switch to command mode with Esc and insert mode with "i", "I", "o", or a variety of other keys.
```
16. In nano, what does Ctrl + O (^O) do?

            a. saves (outputs) the file

            b. creates a blank (original) file

            c. searches for a term (object)

            d. closes (obfuscates) the editor
```
Correct: a
Some of the nano commands are not very intuitive. Luckily, the menu bar at the bottom of the screen reminds us of some common tasks.
```
17. In nano, where are common commands listed?

            a. along the top of the screen

            b. at the bottom of the screen

            c. nowhere

            d. in the man pages
```
Correct: b
As you resize the terminal, you'll see more or fewer commands.
```
18. How would you alter the below code to add numbers to the output lines?
```
grep "the" poems.txt
```
            a. grep -n "the" poems.txt

            b. grep -n poems.txt

            c. grep -a "the" poems.txt

            d. n -grep "the" poems.txt
```
Correct: a
This command will number the output lines where the word "the" is found in the file poems.txt.
```
19. To show the lines from the file report.txt which contain the numbers 1, 2, or 3, what should you write?

            a. grep "123" report.txt

            b. grep -E "[123]" report.txt

            c. grep 123 report.txt

            d. grep report.txt "[123]"
```
Correct: b 
This command uses a regular expression rather than a literal string match.
```
20. What is the best command for modifying information from a file or stream?

            a. tail

            b. sed

            c. sort

            d. cat
```
Correct: b
sed is a good choice if you need to modify information.
```
21. In an Awk program, the term $3 represents _____.

            a. the contents of the fourth field on each line

            b. the contents of the third field on each line

            c. three dollars

            d. the entire third line of a file or stream
```
Correct: b
Awk is helpful for extracting information from well-formatted text streams.
```
22. To switch from insert mode to command mode in Vim, press _____.

            a. q

            b. Esc

            c. !

            d. :
```
Correct: b
When you switch to command mode from insert mode, the --INSERT-- indicator will disappear from the lower left corner of the screen.
```
23. What should you write to show the lines from the file report.txt which match the search term "completed"?

            a. grep report.txt "completed"

            b. grep "completed" report.txt

            c. grep report.txt

            d. grep "completed"
```
Correct: b
While the double quotes aren't necessary, it's a good practice to use them.
```
24. You are in your home directory and have typed the command ls -h. What output will result from typing this command?

            a. Files beginning with a / in the home directory will be displayed.

            b. All files in the filesystem root directory will be displayed.

            c. Files with names beginning with a period in the home directory will be shown.

            d. Files in the home directory will be displayed, with their sizes represented in human-readable units.
```
Correct: d 
```
25. On a Linux system, the PATH environment variable represents _____.

            a. locations which the shell will search for executable programs

            b. a list of all of the directories on a filesystem

            c. the root of the filesystem

            d. the current working directory
```
Correct: a
Without being able to search in the PATH, we would have to type out the full path to common tools every time we used them.
```
