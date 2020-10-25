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

now, in your terminal/command prompt go to folder where you want to place project.
```
$ cd Desktop/projects
```
### There are two ways to include git in projects:

- **_clone the repository_**(simpler way, no hassel)

copy the Github_repository_URL for the repositry you just created.
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

Now that we are finished with including git, you can continue with your project and 

**_Next part is for commiting_(uploading to github) the changes you have made in your project.**
  * ### Add files to the staging area for commit.
    To add all the files the directory(folder):
    ```
    $ git add .   
    ```
    To add a specific file. For example, readme file:
    ```
    $ git add README.md
    ```
  * ### Check which files are staged.
    ```
    $ git status
    ```
  * ### Commit changes you have made to your git repo.
    "first commit", the message in the below command will be visible to read in the repository. Type useful message to show what changes you have made.    
    ```
    $ git commit -m "First commit"
    ```
  * ### Uncommit and unadd files.
    use this command if you want to undo a wrong commit, after this command you will have to start over with adding files to stage.
    ```
    $ git reset HEAD
    ```
  * ### add remote origin and push.
    here, we are connecting the repository.
    ```
    $ git remote add origin Github_repository_URL
    ```
    And here, pushing our code into github.
    ```
    $ git push -u origin master
    ```
## And now if you go and check our repository page on GitHub
you will find your code uploaded into the repository.
