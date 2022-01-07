# GitTutorial

# push, commit, rebase, merge, add, revert, log, diff

git stash -> command takes uncommit changes(changes that you have just added) saves them in a working
                directory and reverts your project to latest committed changes.

git stash pop -> it is used to bring back the changes that we saved using git stash.

git stash clear -> used to delete changes that we saved using git stash.

git restore --staged .  -> this commands is used to undo changes that we added using git add .

.git folder is used to keep track of your project versions(history)

git log -> used to see your all time different versions of your project

git reset (commit_hascode) ->  used to remove all changes that we commit after that commit_hascode.
                                It brings back the project to that particular committed version. 

git status -> current status of your project directory.

git remote -v -> will display all urls linked to that directory.

git push origin master -> {
    origin stands for which url do you want to push.
    master represents which branch do you want to push.
}

git branch feature -> used to create a new branch with name 'feature'

git checkout feature, git checkout main -> used to shift between braches for committing.
                            After checkout to a particular branch, all commits will go to that branch
                            branch. HEAD pointer is used to point to brach on which the commits will be saved.

git merge feature -> used to merge a branch named 'feature' to main branch
