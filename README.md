# gitTest
This Project is created for testing git command.

**1.show the status of files in workplce and cache**
```
git status
```

**2.show the modified content**
```
git diff
```

**3.remove file**
```
#remove from cache and workplace.(file was added to cache)
git rm -f <filename>

#remove from workplece, but stil need to commit changes.(file was commited to cache)
git rm <filename>
```

**4.add file to the cache**
```
$git add <filename>

# add all changes to the cache, include deleting files.
$git add .
```

**5.commit files from cache to repository, -m is meaned the information**
```
git commit -m 'some information'
```

**6.show history**
```
git log
```
