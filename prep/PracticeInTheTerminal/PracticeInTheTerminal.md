# Practice In the Terminal

## The Command Line
A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.

The command line typically presents you with a prompt. As you type, it will be displayed after the prompt. Most of the time you will be issuing commands.
Within a terminal you have what is known as a shell. This is a part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you.

## Basic Navigation
- **pwd**
Print Working Directory - ie. Where are we currently.
- **ls**
List the contents of a directory.
- **cd**
Change Directories - ie. move to another directory.
- **Relative path**
A file or directory location relative to where we currently are in the file system.
- **Absolute path**
A file or directory location in relation to the root of the file system.
- **Tab**
When you start typing a path (anywhere on the command line, you're not just limited to certain commands) you may hit the Tab key on your keyboard at any time which will invoke an auto complete action.

## More About Files
- **file**
obtain information about what type of file a file or directory is.
- **ls -a**
- List the contents of a directory, including hidden files.
- Everything is a file under Linux
Even directories.
- Linux is an extensionless system
- Files can have any extension they like or none at all.
- Linux is case sensitive
- Beware of silly typos.

## Manual Pages 
The manual pages are a set of pages that explain every command available on your system including what they do, the specifics of how you run them and what command line arguments they accept.
To exit the man pages press 'q' for quit.
man command
Look up the manual page for a particular command.
man -k search term
Do a keyword search for all manual pages containing the given search term.
/term
Within a manual page, perform a search for 'term'
n
After performing a search within a manual page, select the next found item.

## File Manipulation
Creating a directory is pretty easy. The command we are after is mkdir which is short for Make Directory.
The command to remove a directory is rmdir, short for remove directory.
To create blank files using the command touch.
The command we use for this is cp which stands for copy.
To move a file we use the command mv which is short for move.
The command to remove or delete a file is rm which stands for remove.
- **mkdir**
Make Directory - ie. Create a directory.
- **rmdir**
Remove Directory - ie. Delete a directory.
- **touch**
Create a blank file.
- **cp**
Copy - ie. Copy a file or directory.
- **mv**
Move - ie. Move a file or directory (can also be used to rename).
- **rm**
Remove - ie. Delete a file
The Linux command line does not have an undo feature. Perform destructive actions carefully.

## Cheat Sheet
quick reminder for the main concepts involved in using the command line and assumes you already understand their usage.