git init
git add .
git commit -m 'First Commit'
git remote add origin git@github.com:ayat-bahii/Lab2.git
git push -u origin main
git switch -c dev
git switch -c test
git switch dev
git add . 
git commit -m "Dev File" 
git push --set-upstream origin dev
git switch test
git add .
git commit -m "test file"
git push --set-upstream origin test
git switch main
git merge dev
git merge test
git push
git branch -d test
git push origin :test
git stash
git switch dev
git stash pop
git tag -a v1.7 -m "version 1.7"
git push origin v1.7
git tag --list
git tag -d v1.7
git push origin --delete v1.7
(make README.md file then add image)
git add .
git commit -m 'Add Image README'
git push 
![IMAGE](https://i.pinimg.com/1200x/23/83/94/238394359525295f3e6ca9cec7ae8a8b.jpg)
