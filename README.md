# github_basics
***Basic functionalities using git***

## 0. Make a github account
if you haven't alredy made one, create [here](https://github.com/join).

## 1. check you have installed git in your machine

open your terminal(mac) and type: 
```
$ git --version
```
if you are using linux(debian), enter this in the terminal
```
$ sudo apt install git-all
```
if you are using windows, get it from [here](https://gitforwindows.org/).

## 2. Introduce yourelf to git

Mention your git uername andemail address, it will be used to identify you when you do *git commit*

Type the following in your terminal or command prompt.
```
$ git config --global user.name "YOUR_USERNAME"
```
```
$ git config --global user.email "ck_cynergy@mail.com"
```
```
$ git config --global --list //To check info you just gave.
```
## 3. Git

Create new repositry on GitHub. [here](https://github.com/new)
now, go to folder where you want to place git using your terminal.
```
$ cd Desktop/projects
```
### There are two ways to include git in projects:

- **_clone the repository_**(simpler way, no hassel)

copy the repository_URL for the repositry you just created.
![alt text](link to clonecopy.img)

Use this command to clone the repository.
```
$ git clone repository_URL
```

### OR

- **_use these commands to create git on any project_**

To add a readme file:
```
$ touch README.md
```
initialise git to the project:
```
$ git init
```

