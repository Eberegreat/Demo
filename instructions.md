//clone project from Github
copy the url --- git clone [paste url]
change directory to the project directory [cd name of the directory]

git status

git add

after adding your text are in staging area -- you need to commit

git commit
git push origin main -- to publish my local commits

/// how to upload our project file using VS code editor
cd ..
cd [new folder]
clear ---- this is to clear terminal

to initialize the git in the project [new folder]
git init

git add . ----- the . ensures all the file in the folder are included in the git

git commit -m "New project created"

/// now we need to upload our new project to github (Remote project)

git remote add origin https.......

paste URL

git branch

to change the branch name from master to main
git branch -M main

git push -u origin main
