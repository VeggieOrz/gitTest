# gitTest
This Project is created for testing git instructions, and there are some git instructions uesed daily.


## Instruction for local operation
###1.initialize git repository
initialize the current directory as a git repository
```
git init
```

###2.show the status of files in workplce and cache
```
git status
```

###3.show the modified content
```
git diff
```

###4.remove file

remove from cache and workplace.(file was added to cache)
```
git rm -f <filename>
```
remove from workplece, but stil need to commit changes.(file was commited to cache)
```
git rm <filename>
```

###5.add file to the cache
```
git add <filename>
```

add all changes to the cache, include deleting files.
```
git add .
```

###6.commit files from cache to repository
-m is meaned the information, the information should not be empty, it's better to descript what changed.
```
git commit -m 'some information'
```

###7.show the submission history
```
git log
```
if you want to reduce output information
```
git log --pretty=online
```

###8.show the instruction history
```
git reflog
```

###9.version rollback
"HEAD" mean the current version, '^' mean back to the last version
```
git reset --hard HEAD^
```
back to a previous version(you should know the commit id)
```
git reset --hard commit_id
```

## Instruction for github operation

###1.clone the project from github
it will initialize a git repository in local dictionary, so we don't need to usethe instruction 'git init'.
```
git clone https://github.com/Username/ProjectName.git
```
## Instruction for Linux

