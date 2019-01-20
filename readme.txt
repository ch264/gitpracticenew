Make folder
Mkdir App

// add folder to git repository
git init
(Press cmd + shift + .  To view hidden folders)

// Stage your code.
git add -A
git add index.html
// adds all files in folder to staging area
Git add .

(You can remove the tracked file in the staging area by typing:
git rm - - cached index.html

// what files are in the staging area
git status

// Create a version of your staged code.
git commit -m 'created game logic'

//Push your code to the GitHub repository.
git push origin master

// How to ignore a file and not add it to staging area even with add .
git .gitignore
touch log.txt
// then add log.txt to the gitignore file and save it.
// add all names of the files that you do not want ot have inlcuded
