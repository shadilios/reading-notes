[Main Readme](https://github.com/shadilios/reading-notes/blob/main/README.md)

# The Command Line

This section explains what a CLI or a terminal is, defines it as a text based interface where you can enter commands and the feedback will be in the form of text instead of effects or sounds like the ones on any GUI.

<br><hr><br>

# Basic Navigation

Now we learn about simple navigation using the terminal (just like accessing our files & folders in windows, but using text).

The main 3 commands discussed here were:

1- pwd: a command that prints the current directory (folder) we are in.  
2- ls: which lists all the files and folders we have in our current path.  
3- cd: which can be used to either enter a specific directory (cd directory-name) or go back with (cd ..).  

<br><hr><br>

# More About Files

This section helps explain the files system & some concepts in Linux, it tells us that Linux looks inside a file/folder to check what it really is (Unlike windows that uses extensions to determine file types).  

It also talks about how we need to use quotation marks with directories that have spaces in them & it also mentions that Linux is case sensitive and how we can access hidden files using the (ls -a) command.  

<br><hr><br>

# Manual Pages

Here, we learn about the Manual that comes with linux and explains and teaches us some commands that we can use in the terminal, such as:  

1- man (command): Looks up the manual for the command.  
2- man -k (search word): Search all the pages with the given search word.  
3- (search word): this is used to search for a (search word) within a specific page.
4- n : just like the search function in the code editor (Ctrl + F3), when you use the n command, you basically tell the terminal to go to the next search result.

<br><hr><br>

# File Manipulation

This Page teaches us (again), the command we learnt in the Prep-course, on how we can manipulate files in Linux (Remove, copy, open & create).

we use (mkdir) & (rmdir) to Make and Remove a folder respectivley.

touch is a command we use to create a file.

cp, mv are used to copy and move files (We can also use cp to rename files).  

rmdir is mentioned in the page as a way to remove directories, but it only works with empty ones.  
to remove a directory that has files inside, we should use the rm -r command.
also, rm is used for files, so we can't use rmdir for files!

<br><hr><br>

