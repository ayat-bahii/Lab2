# Git & GitHub Lab 2

## 1. Initialize Repository and Push to GitHub

```bash
git init
git add .
git commit -m 'First Commit'
git remote add origin git@github.com:ayat-bahii/Lab2.git
git push -u origin main
```

## 2. Create and Switch Between Branches

```bash
git switch -c dev
git switch -c test
git switch dev
```

## 3. Add and Push Changes to the Dev Branch

```bash
git add .
git commit -m "Dev File"
git push --set-upstream origin dev
```

## 4. Add and Push Changes to the Test Branch

```bash
git switch test
git add .
git commit -m "test file"
git push --set-upstream origin test
```

## 5. Merge Branches into Main

```bash
git switch main
git merge dev
git merge test
git push
```

## 6. Delete the Test Branch

```bash
git branch -d test
git push origin :test
```

## 7. Stash Changes and Switch Branches

```bash
git stash
git switch dev
git stash pop
```

## 8. Delete the Dev Branch

```bash
git branch -d dev
git push origin :dev
```

## 9. Create and Push a Version Tag

```bash
git tag -a v1.7 -m "version 1.7"
git push origin v1.7
git tag --list
```

## 10. Delete the Version Tag

```bash
git tag -d v1.7
git push origin --delete v1.7
```

## 11. Create README.md and Add Images

### Image from URL

![IMAGE](https://i.pinimg.com/1200x/23/83/94/238394359525295f3e6ca9cec7ae8a8b.jpg)

### Local Image

![Local Image](image.jpg)

## 12. Commit and Push README.md

```bash
git add .
git commit -m 'Add Image README'
git push
```
