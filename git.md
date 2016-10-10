# Git Cheatsheet
## Commants

    | Git commands                 | Function
    | :--------------------------- | :--------------------------- |
    | **Base commands** | |
    | `git init` | Make project
    | `git status` | Status

## Stepps
### rebase
    - git checkout branchname
    - git fetch
    - git rebase master
    - git checkout master
    - git merge admin
    - CONFLIST
    - resolve
      - git add file.txt
    - git rebase --continue

### rebase split the file
    - git rebase -i HEAD~4
    - set pick to edit in file
    - git reset --soft HEAD^
    - recommitted changes so add file 1 add file 2
    - git rebase -- continue

### rebase files combine
    - git rebase -i HEAD~4
    - set edit in file last commit down
    - set comment

## update fork after pull request
    - git remote add upstream pathToRepo
    - git fetch upstream
    - git merge upstream/master master
    - git push origin master
    - git pull upstream master

    - git fetch
    - git branch -a (list branches)
    - git checkout branchNAAM
    -
