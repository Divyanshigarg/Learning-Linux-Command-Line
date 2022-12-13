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

            a. They allow us to combine files in a space-saving way, and are commonly used when we exchange files with other platforms 
            or across the internet.

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











