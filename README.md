# gitTest
This Project is created for testing git commands, and there are some Git commands uesed daily.


## Command for local operation
### 1.Initializing git repository
Initialize the current directory as a git repository, and it will create a new subdirectory named .git that contains all of your necessary repository files
```
git init
```

### 2.Checking the status of your files
Show the status of files in workplce and stage
```
git status
```

### 3.Seeing the modified content
```
git diff
```

### 4.Removing files
Remove from stage and workplace.(file was added to stage)
```
git rm -f <filename>
```
Remove from workplece, but stil need to commit changes.(file was commited to stage)
```
git rm <filename>
```

### 5.Adding file to the stage
Add some changes in <file> to the stage.
```
git add <file>
```

Add all currrent changes to the stage, include deleting files.
```
git add .
```

### 6.Commiting files from stage to repository
-m is meaned the information, the information should not be empty, it's better to descript what changed.
```
git commit -m 'some information'
```

### 7.viewing the commit history
```
git log
```
if you want to reduce output information
```
git log --pretty=online
```
Show changs over time for a specific file
```
git log -p <file>
```

### 8.Showing the command history
```
git reflog
```

### 9.version rollback
"HEAD" mean the current version, '^' mean back to the last version
```
git reset --hard HEAD^
```
back to a previous version(you should know the commit id)
```
git reset --hard commit_id
```

## Command for github operation

### 1.Cloning an existing repository from github
it will initialize a git repository in local directory, so we don't need to usethe command 'git init'.
```
git clone https://github.com/Username/ProjectName.git
```
## Command for Linux

