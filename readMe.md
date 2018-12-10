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
