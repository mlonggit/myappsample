1$git init

2.$ git init
$git config --global user.name 'mike long'
$git config --global user.email 'mcklong@hotmail.com'

// add file to git
$git add index.html

//check status on staging
$git status

$git rm --cached index.html
//remove file and check status...
$git status

// add all html files
$git add *.html

// add all files
$git add .

$git commit
i    // to insert

esc
:wq  //to exit

// make commit skip editing stage...-m include comment 
git commit -m 'Changed app.js'


//how to use git ignore
$touch .gitignore


//create log.txt dir1 dir1
add log.txt to gitignore 
add dir2 to ignore

git add *.html // add all .html files
git commit -m 'another change'

//branch
$git branch login

//switch to branch
$git checkout login

// create file in login branch
$touch login.html

modify index.html
save
$git add .

$git commit -m 'login form'


//////////
//switch back to master
$git checkout  master
//the login and index changes not in master

// to merge
$git merge login
// login and index changes should be shown


//remote acess
create new git repository
>mygitapp


$git remote //nothing yet

git remote add origin https://github.com/mlonggit/mygitapp.git
git push -u origin master


//////////////////////////
$ git remote add origin https://github.com/mlonggit/myappsample
fatal: remote origin already exists.

//do this
git remote rm origin
//then

git remote add origin https://github.com/mlonggit/myappsample.git
git push -u origin master

!! works finally !!!