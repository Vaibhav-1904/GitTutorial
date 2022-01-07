# Git and GitHub Notes

- **.git folder** is used to keep track of your project versions(history)

- **git status** -> current status of your project directory.

- **git log** -> used to see your all time different versions of your project

- **git reset (commit_hascode) ->** used to remove all changes that we committed after that commit_hascode.
                                It brings back the project to that particular committed version.

- **git stash ->** command takes uncommit changes(changes that you have just added), saves them in a working directory and reverts your project to previous committed changes.

- **git stash pop ->** it is used to bring back the changes that we saved using git stash.

- **git stash clear ->** used to delete changes that we saved using git stash.

- **git restore --staged .  ->** this commands is used to undo changes that we added using git add . 

- **git remote -v ->** will display all urls linked to that directory.

- **git push origin master ->** {
    origin stands for which url do you want to push.
    master represents which branch do you want to push.
}

- **git branch feature ->** used to create a new branch with name 'feature'

- **git checkout feature, git checkout main ->** used to shift between braches for committing changes.
                            After checkout to a particular branch, all the new commits will go to that branch. HEAD pointer is used to point to branch on which the new commits will be saved.

- **git merge feature ->** used to merge a branch named 'feature' to main branch

- **git pull upstream master** -> {
    - If you have forked any project and if someone else or the owner of the project updates the project(add new commits), then your forked repository will be behind the main project. The command is used to pull all the changes to your working directory in the machine.
    - Or you can also do fetch upstream, it will fecth the data and keep your Remote repo updated.
}


---

### Fork a Repository

- **git clone 'url' ->** used for working on someone else's project. Clone a Project available on GitHub, copy it to any Directory on your Machine.

- **git remote add upstream 'url ->'** It is used to add the upstream url to your working Directory.

**Note :** From where you have Forked the 'url' is known as upstream url. If you have forked a url from **abc's** account and repository name is **xyz**, then upstream url is the **xyz's** url available on that Repository.

---
### Pull Request

- Fork the Project to which you want to send the **pull request**.
- Use **git clone and git remote add upstream** to add it in your personal machine.
- Create a new branch for the new things(feature), for which you want to contrbiute/send pull request.
    - *git branch feature*
    - *git checkout feature* ->  used to switch to feature branch.
- Add new code changes.
- push the changes to the *feature* branch.
    - *git push origin feature*
- Compare and send the pull request to the main branch of the Original Account's Project.



### Commands left to be referred: 

 - git push, commit, rebase, merge, add, revert, log, diff