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

git push -u origin main ------ uploading our project to our main repository main branch /// [-u] the means we are setting it in default

// what is git branch
suppose you hire two developer to build a new feature in your app. you will create two branches for them to create, after creation you will review the codes before mergeing in the main branch

// create new brancj we already have one branch which is main

git checkout -b feature1
git checkout -b feature2

now check the branches available
git branch

// to switched to any branch --- now switching to main branch

git checkout main

git push origin feature1

//to add our files in feature1

git add .

// to commit changes

git commit -m "Added p tag"

// to post the commit

git push origin feature1
