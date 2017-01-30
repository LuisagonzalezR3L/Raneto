---
---
This project is intended to allow new devs to learn how to use git and pull request methodology.

## Pull request ##

**_1._** You should create a branch(Always the branch name must has the initials of your name  **/** the ticket, for example **lg/readme**)  
```sh
git checkout -b <banchName>
```  
**_2._** You should create a message referring to the actions. 
```sh
git commit -a -m "<Your message>"
```  
**_3._** You should upload changes using the command:  
```sh
git push origin <branchName>
```  
**_4._** You should visit [BITBUCKET](https://bitbucket.org/account/signin/) web page.  
**_5._** Here you find the option **Create pull request** you should click on the option.  
**_6._** You should choose the brand, write a title and write the description (Always you must specify what is the development and how can proof the functionality).  

## Git ##
[comment]: # (This is a comment in Markdown)

### Change the name of a branch ###  
```sh
git branch -m <oldBranchName> <newBranchName>
```  
### Delete a branch ###  
```sh
git branch -d <branchName>
```  
or  
```sh
git push origin: <branchName>
```  
### List all the branches ###  
```sh
git branch
```  
### Switch from one branch to another 
```sh
git checkout <branchName>
``` 
### Add all files  
```sh
git add .
```  
### Add one file  
```sh
git add <fileName>
```  
### Clone a repository  
```sh
git clone
```  
### List the files you've changed  
```sh
git status 
```  
### Create a repository  
If you create a repository you have the option to upload your project with the commands:
```sh
git remote add origin
```  
It is for choose location in your repository, it can take the remote name or a remote URL.  
```sh 
git push -u origin master
```  
It is for complete the upload process.  
### Config user ###

First time, you should config your username and your email

|**Username**                             |**Email**                                 |
|:---------------------------------------:|:----------------------------------------:| 
|git config --global user.name "Your name"|git config --global user.email Your email |