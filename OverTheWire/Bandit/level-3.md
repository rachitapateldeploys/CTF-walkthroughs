# Bandit - Level 3
**Level Goal**

The password for the next level is stored in a hidden file in the inhere directory.

**Commands you may need to solve this level**  
`ls:` Lists files and directories.  
`cd:` Changes the current directory.  
`cat:` Displays the contents of the a file.  
`file:` Shows the file type of given file.  
`du:` Displays disk usage of files/directories.  
`find:` Searches for files and directories based on criteria.  
Note: To learn more about the commands, use the man command in the terminal.  

`man command_name`

# Solution
Use SSH to login from the server with the following information.

Username: `bandit3`  
Password: `MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx`  
Host: `bandit.labs.overthewire.org`  
Port: `2220`  

**Command:** `ssh bandit3@bandit.labs.overthewire.org -p 2220`   

Once logged-in use the appropriate commands to find the directory named `inhere` and view the content of the hidden file:
- Use `ls` to verify if the intended directory is present or not.  
  `ls`
  
- Use `cd` to navigate to the `inhere` directory.  
  `cd inhere`
  
- Use the following command to with `-a` option to view hidden file.  
  `ls -a`
  
- Use the following command to view the file content.  
  `cat ./...Hiding-From-You`  

Password: `2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ`  

![level 3 solution](../Images/level3-sol.png)  
