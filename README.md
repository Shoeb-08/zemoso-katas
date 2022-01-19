# zemoso-katas
**Kata 1 - Basic Commits**
```
1) to add files
git add FileName.extension
git status


2) to create new files
touch CreateNewFile

3) to commit message
git commit -m "message"

4) to Overwrite a file
echo contentToAdd > fileName

5)to append a file
echo contentToAdd >> fileName


```

**kata 2 - Staging**

**working directory->staging area-> epository**
```
git diff
git diff --staged
git restore --staged file.txt


```

**kata 3 - branching**
```

1) to create a new branch
git branch (or) git checkout -b new_branch

2) to switch branches

git switch

3) to see the branch  
git branch

```




**kata 4 - ff merge**
```
git commit
git commit -m
git merge <branch>
git diff <branchA> <branchB>
git log --oneline --graph --all



```




**kata 5 - 3 way merge**
```
git add
git commit
git commit -m
git merge <branchA> <branchB>
git diff <branchA> <branchB>
git log --oneline --graph --all


```




**kata 6 - merge conflict**
```
git merge
git status
git add
git commit
git log --oneline --graph

```

**kata 7 - merge-mergesot**
```
git status
git mergetool --tool=emerge
git mergetool --tool=vimdiff
git add
git commit


```
**kata 8 - rebase-branch**
```
git checkout <branch-name>
git rebase <branch-name>
git log --oneline --graph --all
git merge <branch-name>

```
**kata 9 - basic-revert**
```
git revert <ref>
git log --decorate --oneline
git show <ref>

```
**kata 10 - reset**
```
git status
git reset --soft
git reset --mixed
git reset --hard
git revert

```
**kata 11 - basic-cleaning**
```
git clean -n
git add
git clean -n -d
git clean -f -d

```
**kata 12 - amend**
```
git log --oneline --graph
git log -p
git show
git commit --amend

```
**kata 13 - reorder the history**
```
git rebase -i <after-this-commit>
git log --oneline --graph
git reflog
```
**kata 14 - squashing**
```
git rebase -i <ref>
git add
git commit --amend

```
**kata 15 - advanced-rebase-interactive **
```
git log --oneline # show history
git log --stat # log which files changed
git log --patch # log with diff
git rebase -i <ref> # run the interactiv

```
**kata 16 - basic-stashing**
```
git diff master
git stash
git stash list
git stash apply
git stash apply --index
git stash drop
git log --oneline --all --graph
git commit
git add

```
**kata 17 - ignore**
```

git commit -m
git rm --cached
```
**kata 18 - submodules**
```
git submodule init
git submodule update

```
**kata 19 - git-tag**
```
git tag
git tag -d <tag>
git tag --list <pattern>
git push --tags <branch>
git rev-parse <tag>
git show

```

