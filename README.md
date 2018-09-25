# Installation

This requires Django and Python3 to work, install Django:
```pip install Django```

# Initialization of Local Host Server
Ensure that you are in the directory where manage.py is located at:
```python manage.py runserver```

Go to your browser and go to 127.0.0.1:8000(aaa.a.a.a:bbbb), where 'a' is IP & 'b' is port.
You should be able to see the page on your browser.

# Using of Git Bash (If you're using git bash)
Ensure that your local repo are always up to date before you start working, i.e. run `git pull` from your own branch

### To commit and push your changes to the remote repository, run the following commands:
```
git add . OR git add --specific file name you like to add--
git commit -m 'Meaningful Commit Message'
git push 
```

### Discard unstaged changes in Git (i.e. Git acknowledges that you have changed some lines of code, you have not run `git add` but you would like to remove the changes)
```
### To unstage one file: `$ git checkout file-name`
### to unstage all files: `$ git checkout --`
```

### To undo a `git add` command
```
git reset HEAD -- OR git reset HEAD file-name
```
