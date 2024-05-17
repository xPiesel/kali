sudo apt update
sudo apt upgrade
sudo apt install git




open a folder and get in to it then use "git init"
create some folders and use ""git add "the name of the folders" or use "." to save all the things in that folder""
use git commit -m 'changes' wrtie up an article about the things you changed -m is the parameter for you to write a message.
remove some and add another folders or etc. and use "git add" and "git commit"


use "git log" to check the date of things you changed
use "git checkout" to see the previous made changes


use "git branch" to make extra leadways
"git checkout -b 'name' " to create a new branch

to use git diff you gotta have 2 same files in 2 different branches
simply use "git diff "file name" "file name"
well you can use diff on 1 file and 1 branch 
1) change something in the branch but dont save it 
later use "git diff 'file name' " to see what is changed
2) change something in the branch and save it with "git add ."
then use "git diff --staged 'file name' " to see what is changed

"git push origin 'name' " to push the branch to github site

now on to pulling them from github
"git pull origin 'branch name' "

