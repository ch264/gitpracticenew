# gitpractice
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


// make Branches e.g. you have to make a login
git branch login (name of branch)



// switch to Branches
git checkout login

(git checkout master (to go back))
()// when going back your new files will be gone from Atom view)



// add files to new Branches
touch login.html



// merge branches while in master
git merge login
// now login file will appear again in Atom



// create a new repository in GitHub
// it will give you the link to add your files
git remote add origin https://github.com/ch264/Appsample.git
git push -u origin master

// make changes to your files and push add, commit, push to GitHub
git push

// clone repository
git clone 'url'

// you can pull all changes from clones to your repository
git pull
