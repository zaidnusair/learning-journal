# An intro to GIT

## Types of Version Control Systems

**Local Version Control**

one database to store changes to files on device.

**Centralized Version Control**

 * a single server to store all changes and files. 
 * can be accessed by various clients.

**Distributed Version Control**

 * allows clients to create mirrored repositories to work as backups.
 * allows multiple mirrored repositories for clients to work together on a projects.


## GIT

GIT is consideredA a *DVCS*, so it stores data on servers its main features are:

1. snapshots
2. relies on local operations 
3. tracks changes
4. minimizes loss of data 
5. resides file in 3 main states: 
  ** commited
  ** modified
  ** staged

### Git can be downlaoded on windows, Mac or linux operating systems.
### Git includes inherent *GUI* tools, but can utilize third-party tools.

## Getting started with GIT

you can control the aspects of Git’s operation and look through the setting of configuration variables using a Git tool called **git config**.

*identity setting*
type this code in your terminal:

`git config --global user.name "Jane Smith"` to assign your name

`git config --global user.email "example@email.com"` to assign you email

`git config --global core.editor TextEditor` to assign text editor

`git config --list` to check your assigned settings

## setting up a Git Repository

*importing*

`$ cd TargettedProject` to switch to target project directory.
`$ git init` to use git init command, you should at this stage have created a new subdirectory named .git
to start tracking:
`$ git add *.c` 
`$ git add LICENCE` 
`$ git commit -m "message here"`

*clonning*

`$ git clone https://github.com/test` to copy all files for a project. a directory with the name *test* will be created
`$ git clone https://github.com/test mydirectory` to clone repository with a name of your choosing

`ls` to check your clone
`cs clone name` to get ro your clone's directory

`filename[master]$` will apeare, this means you're inside your clone file

*coding your clone locally*

type `code .` on terminal while you're inside your clone's folder

**this will open VS code**
you can start coding your file using VS code 

*commiting*
type `git status` to check files that need to be added, modified file will apeare in **red**
type `git add filename` to add the changes made on this file to the could
type `git status' to check, files moved will apeare in **green**
type `git commit -m "filename.extension"` to commit your changes



