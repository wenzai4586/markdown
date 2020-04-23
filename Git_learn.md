<!--
 * @Description  : 
 * @Version      : 
 * @Author       : yan_wen
 * @Date         : 2020-03-18 14:04:31
 * @LastEdiors   : yan_wen
 * @LastEditTime : 2020-04-21 21:46:57
 -->
# learn git
## normal handle
- git init
- git add
```
    -i, --interactive     interactive picking
    -p, --patch           select hunks interactively
    -e, --edit            edit current diff and apply
    -f, --force           allow adding otherwise ignored files
    -u, --update          update tracked files
    -N, --intent-to-add   record only the fact that the path will be added later
    -A, --all             add changes from all tracked and untracked files
    --refresh             don't add, only refresh the index
    --ignore-errors       just skip files which cannot be added because of errors
    --ignore-missing      check if - even missing - files are ignored in dry run
```
- git commit
```
        git commit text.txt -m "something about your commit"
        git commit --amend            amend the message
        git commit -am message        add and commit
```
- git status
- git diff
```
ex:     git diff HEAD                 diff between last time
```
- git log
```
ex:     git log file
        git log --pretty=short        short message
        git log -p file               log and diff
        git log --graph               see the merge and other log

```
- git reflog
```
        know the handle history
```
- git rm
```
        git rm file
```
- git branch
```
            show all the branch and where we are
```
- git checkout
```
        -b branchA                    create the branchA
ex:     git checkout master           choose go to master
        git checkout -                backward to last
        git checkout -b branchA origin/branchA   get the branch from github
```
- git merge
```
        merge your branch and master
ex:     git merge --no-ff branchA       commit this time merge

```
- git reset
```
ex:     git reset --hard haxinum(only4)

        
```
- git rebase
```
        rebase several commit message to one message
        git rebase -i HEAD~2          add to the last commit
```
- git remote add origin ssh
```
        git remote add origin git@github-...
```
- git push
```
        git push -u origin master     connect master with github
```
- git clone
```
        git clone ssh                 get the master
```
- git introduction
```
	git has two branch:
		1. mainstay
		2. character branch
```

