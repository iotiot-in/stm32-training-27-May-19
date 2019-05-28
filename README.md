# Introduction
This project contains notes from the STM32 tarining held on 27th & 28th May 2019.

# Motivation 
IoTIoT.in is a comminity which promotes collabration, we believe collaborating all our 
notes, resources will make the comminity members grow stronger.

# How to contribute to this project ?

## Pre-requisites 

Make sure your laptop has git installed 

#### Git Installation
Check out the instructions on how to install git 

For Windows go to this [link](https://www.toolsqa.com/git/install-git-on-windows/)

For Linux go to this [link]()

# Step 1 : Write Documents

## Topics to document


## Files that we accept 
People who are familiar with Markdown, Please write your documentation in Markdown else Word doc is also acceptable. 

1. `.md` (Markdown file) (Preferred)
2. `.doc` (Microsoft Word file)

# Step 2: Add your documentation to our Repository 

Please use these steps to contribute to the project.

1. Clone
2. Create Your Branch
3. Insert/Edit your contents
4. Commit 
5. Push to your branch

### 1)Clone 
```
$ git clone https://github.com/iotiot-in/stm32-training-27-May-19.git 
```
### 2a)Create Your Branch (first time)
```
$ git checkout master            	//To checkout if you are on master branch
$ git checkout -b <your-name>      	//To create a new branch and move into it 
```
### 2b)Working on Your Branch (Regular workflow, after branch is created )
```
$ git branch -a               	//To see all  branches
$ git checkout <your-name>     //To switch to branch <your-name>
```
### 3)Make changes and commit inside the repository
```
$ git status        //Check the files to which you made changes .
$ git add .         //To add untracked files( . adds all files)
$ git commit -sav   //Description about the commit 
$ git branch -a 	// Confirm working on your own branch & not master

```
### 4)Push changes to your branch
```
$ git push origin <branch-name>    	// push changes into repository into your own branch  

```

# License 

GPLv3 Please check the project [License](LICENSE.md)
