---
layout: default
title: UNIX Tutorial One
nav_order: 2
parent: Linux tutorials
---

# Unix Tutorial One
  
## 1.1 Listing files and directories
### ls (list)  
When you first login, your current working directory is your home directory. Your home directory has the same name as your user-name, for example, **ee91ab**, and it is where your personal files and subdirectories are saved.  
  
To find out what is in your home directory, type  
% **ls** (short for list)  
  
The **ls** command lists the contents of your current working directory.  
  
There may be no files visible in your home directory, in which case, the UNIX prompt will be returned. Alternatively, there may already be some files inserted by the System Administrator when your account was created.  
  
**ls** does not, in fact, cause all the files in your home directory to be listed, but only those ones whose name does not begin with a dot (.) Files beginning with a dot (.) are known as hidden files and usually contain important program configuration information. They are hidden because you should not change them unless you are very familiar with UNIX!!!  
  
To list all files in your home directory including those whose names begin with a dot, type  
% **ls -a**  
  
**ls** is an example of a command which can take options: **-a** is an example of an option. The options change the behaviour of the command. There are online manual pages that tell you which options a particular command can take, and how each option modifies the behaviour of the command. (See later in this tutorial)  
  
  
## 1.2 Making Directories
### mkdir (make directory)  
We will now make a subdirectory in your home directory to hold the files you will be creating and using in the course of this tutorial. To make a subdirectory called cs1 in your current working directory type  
% **mkdir cs1**  
  
To see the directory you have just created, type  
% **ls**  
  
  
## 1.3 Changing to a different directory
### cd (change directory)  
The command **cd {directory}** means "change the current working directory to 'directory'. The current working directory may be thought of as the directory you are in, i.e. your current position in the file-system tree.  
  
To change to the directory you have just made, type  
% **cd cs1**  
  
Type **ls** to see the contents (which should be empty).  
  
### Exercise 1a  
Make another directory inside the **cs1** directory called **backups**  
  
  
## 1.4 The directories . and ..  
Still in the **cs1** directory, type  
% **ls -a**  
  
As you can see, in the **cs1** directory (and in all other directories), there are two special directories called "." and ".."  
  
In UNIX, "." means the current directory, so typing  
% **cd .** (NOTE: there is a space between cd and the dot)  
means stay where you are (the cs1 directory). This may not seem very useful at first, but using "." as the name of the current directory will save a lot of typing, as we shall see later in the tutorial.
