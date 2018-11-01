<h1>Command Line Syntax</h1>

`[prompt]$ command option argument`

<h1>The `echo` Command</h1>

To print to the screen you can use the syntax:

`echo stringYouWantToPrint`

For example:
* `echo hello`
* `echo "Hello, how are you doing?"`
* `echo 'Hola, como estas?'`

<h1>Getting Out of Infinite Loops</h1>

There are times when you will be working the terminal where the terminal gets stuck or 'hangs'. 

Commands that could cause the terminal to hang:
 * `$ echo "hello`
 * `$ yes`
 * `$ cat`

 To get out of the 'hang' you will need to push down `ctrl + c`

<h1>Clearing the Terminal</h1>

Sometimes you need a fresh start on the terminal. In order to clear the commands on the screen, type in the command `$ clear`, the keyboard shortcut is `^L`.

When you are done with a terminal window (or tab) and are ready to exit, type in the command `$ exit`. A keyboard shortcut is `⌃D`.

<h1>Commands for Navigation</h1>

The following commands are some of the most commonly used commands for navigating through the terminal:

* `$ ~` - will take you the root directory
* `$ cd` - Changes the directory that you are in, for example:
    * `$ cd Desktop` will change the directory from the current directory to the Desktop directory
    * `$ cd ..` will go back one directory above the current
* `$ ls` - abbreviation for list, will list all the files and directories in the current directory
    * `$ ls -l` - will list long form	
    * `$ ls -rtl` - will list long by reverse modification time
    * `$ ls -a`	- will list ALL files, including hidden files

<h1>File and Directory Manipulation</h1>

There are many commands we can use to create, update, move, copy, and delete files. Below are some of the most commonly used:

<h3>File Commands</h3>

* `$ touch <file>` -	will create an empty file	
* `$ cp <old> <new>` -	will copy the contents of the old file and write over the contents of the new file
* `$ open <file>` - will open the file in its default application
* `$ rm <file>` -	will remove a file	
* `$ rm -f <file>` -	will force-remove file

<h3>Directory Commands</h3>

* `$ mkdir <directory>` -	will create an empty directory	
* `$ open <directory>` - will open the directory in the finder window
* `$ rmdir <directory>` -	will remove the directory  ONLY if there are no subfiles or subdirectories.	
* `$ rmdir -r <directory>` -	will remove the directory AND it's contents

<h1>Exercises</h1>


1. Write a command that prints out the string “Bonjour, cherie”.

2. Type the command `echo 'Hey there, partner` (with a mismatched single quote), and then get out of the stuck loop.

3. Clear the contents of the current tab.

4. Start at the root directory and changes directories to your Documents directory.

5. Navigate to your Desktop in the terminal and list all of the files and directories in your Desktop, including your hidden files.

6. Navigate to your Desktop and create three empty files: fileOne.txt, fileTwo.txt, and fileThree.txt. Open fileOne.txt and write some content onto the file. Then copy the contents of fileOne.txt to fileThree.txt, the remove fileOne.txt and fileTwo.txt.

7. Navigate to your Desktop and create a new directory called "portfolio". Navigate inside of that directory and create the following three files: index.html, style.css, script.js. <br>
_Extra Credit: Open the portfolio directory in your text editor through the command line._

8. Remove the portfolio directory you created in Number 7.

<h1>Extra Resources</h1>

* Learn Enough Command Line to be Dangerous - https://www.learnenough.com/command-line-tutorial

* Mac Command Line Cheat Sheet -https://gist.github.com/poopsplat/7195274

* Windows Command Line Cheat Sheet - https://www.thehackr.com/windows-cmd-cheat-sheet/