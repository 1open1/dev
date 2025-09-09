# 📘 Git Commands (DevOps Unit 2)

A quick reference guide for essential Git commands.

---

## 🔹 Check Git Version
```bash
git --version
```

---

## 🔹 Configure Git (Global)
```bash
git config --global user.name "xyz"
```
```bash
git config --global user.email "xyz@gmail.com"
```

---

## 🔹 Configure Git (Local)
```bash
git config user.name "xyz"
```
```bash
git config user.email "xyz@gmail.com"
```

---

## 🔹 Create Local Repository
```bash
git init
```

---

## 🔹 Untrack Repository
```bash
rm -rf .git
```

---

## 🔹 Add Remote Repository
```bash
git remote add origin "URL-of-Remote-Repository"
```

---

## 🔹 Pull from Remote (if not empty)
```bash
git pull origin master
```

---

## 🔹 Remove Remote Repository
```bash
git remote remove origin
```

---

## 🔹 Check Remote Repositories
```bash
git remote -v
```

---

## 🔹 Create File
```bash
vi newfile.txt
```
```bash
vi ignore.txt
```

---

## 🔹 Ignore File
```bash
echo "ignore.txt" >> .gitignore
```

---

## 🔹 Check Status
```bash
git status
```

---

## 🔹 Add Files to Staging
```bash
git add filename.txt
```
```bash
git add -A
```
```bash
git add .
```

---

## 🔹 Remove Files from Staging
```bash
git reset filename.txt
```
```bash
git reset
```

---

## 🔹 View Changes
```bash
git diff
```

---

## 🔹 Commit Changes
```bash
git commit -m "commit message"
```

---

## 🔹 View Commit History
```bash
git log
```

---

## 🔹 Pull from Remote
```bash
git pull origin master
```

---

## 🔹 Push to Remote
```bash
git push origin master
```

---

## 🔹 Create Branch
```bash
git branch newbranch
```

---

## 🔹 Switch Branch
```bash
git checkout branch-name
```

---

## 🔹 List Branches
```bash
git branch
```
```bash
git branch -a
```

---

## 🔹 Push Branch to Remote
```bash
git push origin branch-name
```
```bash
git push --all origin
```

---

## 🔹 Merge Branch into Master
```bash
git checkout master
```
```bash
git pull origin master
```
```bash
git merge mergebranch
```

---

## 🔹 Rebase Branch into Master
```bash
git checkout master
```
```bash
git rebase rebasebranch
```

---

## 🔹 Delete Branch (Local)
```bash
git branch -d branch-name
```

---

## 🔹 Delete Branch (Remote)
```bash
git push origin --delete branch-name
```

---

## 🔹 Undo Changes
```bash
git checkout filename.txt
```

---

## 🔹 Amend Last Commit
```bash
git commit --amend -m "Updated Message"
```

---

## 🔹 Reset Commits
```bash
git reset --soft commit-hash
```
```bash
git reset commit-hash
```
```bash
git reset --hard commit-hash
```

---

## 🔹 Clean Untracked Files
```bash
git clean -df
```

---

## 🔹 Reflog & Recovery
```bash
git reflog
```
```bash
git checkout commit-hash
```
```bash
git branch backup
```

---

## 🔹 Revert Commit
```bash
git revert commit-hash
```

---

## 🔹 Diff Commits
```bash
git diff commit1-hash commit2-hash
```

---

## 🔹 Stash Changes
```bash
git stash save "message"
```
```bash
git stash list
```
```bash
git stash apply stash@{id}
```
```bash
git stash pop
```
```bash
git stash drop stash@{id}
```
```bash
git stash clear
```

---

## 🔹 Diff Tool
```bash
git difftool master
```
```bash
git difftool commit1 commit2
```
```bash
git difftool origin/master
```

---

## 🔹 Clone Repository
```bash
git clone "URL-of-Remote-Repository"
```
```bash
git clone "URL-of-Remote-Repository" desktop/gitrepo1
```
