# All this pages are about how to use __git__, a code manager.
## clone a repo or project
```shell
git clone <Git repo URL>
```
## Quick Start for my github
- step 1: create a new repository in your github
- step 2: select your directory your want to upload
```shell
# initilize your dir
git init
# add all your new files
git add .
# commit your changes
git commit -m "<messages about this commit>"

# push your changes t remote repo 
# firstly
git remote add origin <your repo url>
git push -u origin main
# normally
git push origin main
```

