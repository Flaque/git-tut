# Git
JUDY has edited the file 
```
 _______  ___  _______               
|       ||   ||       |              
|    ___||   ||_     _|              
|   | __ |   |  |   |                
|   ||  ||   |  |   |                
|   |_| ||   |  |   |                
|_______||___|  |___|                
 ___  _______                        
|   ||       |                       
|   ||_     _|                       
|   |  |   |                         
|   |  |   |                         
|   |  |   |                         
|___|  |___|                         
 _______  __   __  ______    ___     
|       ||  | |  ||    _ |  |   |    
|    ___||  | |  ||   | ||  |   |    
|   | __ |  |_|  ||   |_||_ |   |    
|   ||  ||       ||    __  ||   |___ 
|   |_| ||       ||   |  | ||       |
|_______||_______||___|  |_||_______|

```


Today we're talking about Git. Git's a tool for sharing code. It's used by *real* industry peoples 
and is the most common tool of its genre.

You may have heard of Git refered to as "source control." That's because git lets you store several 
versions of your code all at once. 

## Prereq: The command line

Although Git does have a GUI, it's generally not a good idea to learn it through the GUI. It's very 
difficult to understand what Git's doing without the shell.

That said, you don't need much command line experience. If you know the following commands, you 
should be good:

```bash 
cd    # "Change Directory"
mkdir # "Make Directory"
touch # makes a new file
ls    # Shows the files in the current directory
```

## Activity Steps

In case you get lost, our activity for today is repeated here.

### Part 1: A Local Repository
This section has nothing to do with Github yet. We're gonna do everything locally.

#### Step 1: Making your own repository

Your goal for this step is to create a new directory, then use `git init` inside that directory
to create your own git project. 

#### Step 2: Add your files

Next, you should create a file that we'll use for our dummy project. If you want, it can be a .java file.
It doesn't need to be correct code. It could also just be a .txt file.

Then, you'll want to `add` it to your current "staging" environment.

#### Step 3: Create a commit 

Next, you'll want to `commit` the things you've added. Then use `status` to check if everyone went okay.

### Part 2: Putting it on the internet

#### Step 1: A new Github repository

On Github, click the "plus" in the top right corner and create "new respository." You can leave most things the default.

Then, use the commands from "push an existing repository" to push up what you made.

#### Step 2: Another Commit

Make some changes to your file, add them and commit them. Then use `push` to send them to the internet repository! 

----------

## Reference

The following is a list of commands we'll be doing today in Git.

```bash 
git status # Tells you the current items in and out of your "staging" environment.
git init # Turns the current directory into a git repository
git add <some_file_path_here> # Adds a file to your "staging" environment (your box!)
git rm <some_file_path_here>  # Removes a file from your "staging"
git commit -m "message here"  # Wraps up your staging environment into a "commit"
git pull # Pulls the repository down from the internet
git push # Pushes your repository up to the internet
git clone <url_here> # Creates a copy of a repository on the internet
```

Also, just in case you need it: 

### How to exit vim

First, press escape. Then press ":", then write ":wq". If you messed up at some point, 
you may need to redo your commit command.


