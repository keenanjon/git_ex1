git clone https://github.com/mattpe/git-intro.git 

cd git-intro

git remote remove origin

git remote add origin https://github.com/keenanjon/git_ex1.git

git branch -M main

git push -u origin main

vim notes.md

git add .

git commit -m 'added notes.md'

git push

vim notes.md
