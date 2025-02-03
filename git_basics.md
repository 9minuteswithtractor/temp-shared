# 📚 GIT - local tool ( distributed versional control system )

`Github`,

`gitLab`,

`Bitbucket`,

     cloud based services
.
    
    gitignore
`.gitignore`

`.vscode`

`vendor/`



## min conf
    git config --global user.email ''
    git config --global user.name ''

# Basic commands :
`git status` - check the latest
`git add .`
`git commit -m ""`
`git commit log` - check history
`git checkout <commit_num>`
`git checkout <branch> || <commitNum>`

`git restore .` - returns the latest 
stable commit 

`git log > <filename.txt>`

`git restore --staged . || <filename>`

`git commit -am 'save and commit all'`

`git status -s` - short status 

`git diff` -  displays the saved but not added / committed changes 

----------------------------------------
# `Branches` :

`git checkout <branchname>`
`git merge feature-1` - merge the latest ..

`git branch <branchName>` - create branch
    source controll on the right side ...set auto ..

`git branch -d <branchName>` - deleting branch / attempt


<!-- !!!!!!!!!!!!!! -->
`git reset HEAD~1` - go back one commit saved changes 
`git reset --hard HEAD~2` -  delete changes no need  
`git reset --hard <commitID>` -

// STASH :
`git stash` - stash the code
`git stash apply` - apply the last stash
`git stash list` - show git stash list
`git stash clear` - iof want to delete all stash list - end of the working day ...

git shortlog 