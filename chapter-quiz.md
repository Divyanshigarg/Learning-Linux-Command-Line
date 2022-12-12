# Chapter Quiz: Learning Linux Basics

1. Unless it's been modified, the shell's prompt string usually shows _____.

        a. the date and time

        b. the username, the host name, and the current working directory

        c. the distribution of Linux you're using

        d. only the current working directory

```
Correct: b
While it may seem redundant, if you're working in a few different shells, having this information readily available can be useful.
```

2. How can you cancel a command you've typed but don't want to run?

          a. Ctrl + Q

          b. Ctrl + X

          c. Ctrl + C

          d. Ctrl + Z
          
```
Correct: c
Ctrl + C is a common way to end or cancel a command.
```
3. To help you look up a command by its description rather than its name, you can use _____.

        a. This is not possible.

        b. which

        c. find

        d. apropos
 ```
Correct: d
Though not many people know about it, apropos is a very helpful tool for beginners and pros alike.
```
4. You enter the command list and receive an error containing suggestions for alternate commands. Why did this happen?


        a. The command you entered had no arguments added to it.

        b. list is not a valid command.

        c. The functionality of the list command is to display alternate command suggestions.

        d. The command you entered had no options added to it.
```
Correct: b
List is not a valid command in Linux, so the shell is trying to suggest alternatives.
```
5. You are trying to list the contents of a directory, but you forget the options you can add to ls. What shows you a brief amount of information about the command you entered?

        a. vi list

        b. man ls

        c. apropos "list"

        d. ls --help
```
Correct: d
```
6. How would you find the manual page for the command ip?

        a. help ip

        b. ip man

        c. which ip

        d. man ip
```
Correct: d
When looking up a command, man is the command, and the command you're looking up is the argument!
```
7. How can you move to the beginning of a line of text?

        a. Ctrl + Z

        b. Ctrl + A

        c. Ctrl + C

        d. Ctrl + E
```
Correct: b
And, remember, you can use Ctrl + E to move to the end of the line.
```
8. To recall a previous command in Bash, you can use _____.

        a. Ctrl + A

        b. Ctrl + Up Arrow

        c. the Up Arrow

        d. Ctrl + E
```
Correct: c
And, you can use Ctrl + R to search within the command history, as well!
```
9. The _____ shell is available on many platforms.

        a. Linux

        b. GUI

        c. Bash

        d. terminal
```
Correct: c
Bash, or the Bourne Again Shell, is widely available and very powerful.
```
10. In the statement df -h /home/alice/Documents, the characters -h represent _____.

        a. an option

        b. a command

        c. a variable

        d. an argument
```
Correct: a
An option is usually specified with one or two dash characters.
```
11. The _____ is where we use the command line interface.

        a. GUI

        b. admin mode

        c. shell

        d. typewriter
```
Correct: c
A command-line interpreter, or shell, accepts commands and displays the results.
```
12. The following string will list all files in the /usr/bin directory. Which part of this string is the argument?
ls -lh /usr/bin

        a. ls

        b. /usr/bin

        c. ls -lh /usr/bin

        d. -lh
```
Correct: b
/usr/bin is the argument for this string.
```
13. Why isn't the statement /home/alice ls -l valid?

        a. Because the ls command does not accept an argument or option.

        b. The command always needs to come first, so this should read ls -l /home/alice

        c. The option should come first, so it reads -l /home/alice ls

        d. This statement is valid.
```
Correct: b
The path to Alice's home directory is an argument when using ls, so it should come last in the sequence of elements of the command.
```
14. What will happen when you type part of a command, and then select Tab?

        a. It will give you an error and make you retype the whole command.

        b. It will autocomplete based on the part of the command you typed.

        c. It will add an argument to the command automatically.

        d. It will add options to the command automatically.
```
Correct: b
Tab completion autocompletes your command based on the first letters of the command.
```






