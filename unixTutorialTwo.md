---
layout: default
title: UNIX Tutorial Two
nav_order: 3
parent: Linux tutorials
---

# Unix Tutorial Two
  
## 2.1 Copying Files
### cp (copy)  
**cp file1 file2** is the command which makes a copy of **file1** in the current working directory and calls it **file2**    
  
What we are going to do now, is to take a file stored in an open access area of the file system, and use the **cp** command to copy it to your **cs1** directory.  
  
First, **cd** to your **cs1** directory.  
% **cd ~/cs1**  
  
Then at the UNIX prompt, type,  
% **cp ~zhang/public_html/cs1600/nytimes.txt .**
  
(Note: Don't forget the dot "." at the end. Remember, in UNIX, the dot means the current directory.)  
  
The above command means copy the file **nytimes.txt** to the current directory, keeping the name the same.  
  
### Exercise 2a  
Create a backup of your **nytimes.txt** file by copying it to a file called **nytimes.bak**  
  
  
## 2.2 Moving files
### mv (move)  
**mv file1 file2** moves (or renames) **file1** to **file2** 
  
To move a file from one place to another, use the **mv** command. This has the effect of moving rather than copying the file, so you end up with only one file rather than two.  
  
It can also be used to rename a file, by "moving" the file to the same directory, but giving it a different name.  
  
We are now going to move the file **nytimes.bak** to your backup directory.  
  
First, change directories to your **cs1** directory (can you remember how?). Then, inside the cs1 directory, type
% **mv nytimes.bak backups** 
  
Type **ls** and **ls backups** to see if it has worked.
