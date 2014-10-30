## Misc

#### Run git from other directory

    git --git-dir /path/to/.git/ push --all bb

#### pull and push all branches

    git push --all origin

## Checkout

#### Checkout single branch

    git checkout --single-branch --branch=BranchName

#### Create new branch with no history

    git checkout --orphan branchName

#### Checkout a remote branch

    git remote update
    git fetch
    git checkout -b local-name origin/remote-name

#### History of directory/file

    git log --all --graph \
    --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset'\n--abbrev-commit \
    --date=relative

#### Git submodule

    git submodule add https://github.com/doctrine/DoctrineBundle.git bundles/DoctrineBundle

#### Release notes

    git log tag1...tag2 --pretty=oneline --reverse --abbrev-commit

## Aliases

    ls = log --oneline
    caa = commit -a --amend -C HEAD

## Resources

1. [Git Succinctly](http://net.tutsplus.com/sessions/git-succinctly/)
1. [Git Cheat Sheet](https://github.com/github/training-kit/blob/master/downloads/github-git-cheat-sheet.pdf)
