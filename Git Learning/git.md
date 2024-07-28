# Git
It is a version controling system.

# Git vs GitHub
Git is s software
github is a service

# Repository (Repo)

# git configurations
to configure git settings
 ```git
git config --global user.name "Gemmy"
 ```
    
 ```git
git config --global user.email "cccontactme1@gmail.com"

 ```
# Git Add
 to add files in staging area
 ```git
 git add <file1> <file 2 >
 ```
 ```git
 git add .
 ```

# Git initialize
one time per project
it create .git => a hidden folder to keep history of all files & subfolders

```git
ls -l -a or
ls -la
```
```git
git init
````
```git
git init -b main
```
# Git Add
 to add files in staging area
 ```git
 git add <file1> <file 2 >
 ```
 ```git
 git add .
 ```
 # git commit
 to commit files, after this it is ready to pus 
 ```git
 git commit -m "your message"
```
# working flow 
working directory --> git add --> staging area --> git commit ---> Repo --> git pus --> gitub 

# Git log
 to see commits
 ```git
 git log
 ```
 ```git
 git log --oneline
 ```
# Atomic Commits 
keep commits centric to one feature, one component or on fix focused on one thing.
present or past message ?
> Depends (present tense, imperative)
> give order to code base
> don't care

