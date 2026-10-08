# Practice Github Commands

This is not a comprehensive introduction to git. There are a lot of great resources out there of how to use git. This repo is intended to give members a low stress sandbox where they can practice commonly used git commands


## What Should You Do?



Practice!


### Commits

1. **Clone the repository**
  -  Before you can make any edits, you first have to clone the repository
  >  `git clone https://github.com/engineering-horizons/github-practice.git`
2. **Create a file!**
  -  You can do this through vscode or the terminal. Its up to you!
  -  Once you have created a new file, you have to "stage" those changes.
  >  `git add 'file-name'`
     - **NOTE**: you CAN use `git add .` to add everything you have modified in 1 command. We recommend NOT doing this because this might add any system files or pre compiled files. 
3. **Commit your changes**
  - Once you have staged all changes, you have to "commit" your changes. This creates a saved stat in your git history of your current code.
  > `git commit -m "some meaningful message"`
4. **Push your changes to `main`!**
  -  After you make a commit, these changes are still only in effect on your local clone of the repository. To add these changes to the remote repository, you have to push.
  > `git push`
     -  **NOTE**: if someone else has made changes and pushed them before you, you might have to `git pull` to update your local copy of the repository before you can push!

### Branches
*Branching gives you an isolated copy of the repository that you can edit completely unaffected by the main branch. This will be how you add features to each repository*

1. Create your branch (**NOTE: `checkout` is used to switch between branches.Using the flag `-b` will create a new branch AND switch your workspace to that branch**)
  > `git checkout -b <branch-name>`
2. Make a commit
  - Practice the skills you just learned above! (Create a new file, Make a change to a file, Your Choice!)
3. Return to the Main Branch
  > `git checkout main`
4. Merge Branches
  - This repository leaves `main` unprotected. So you can push your changes directly to the `main` branch. However, this is not best practice and is not how you will be working on your projects. Since merging branches is an important skill, you should still practice the commands!
  > `git merge <branch-name>`
5. Delete the branch
  - Once you have successfully merged your branch, you should delete the branch to keep the repository uncluttered and clean. 
  > `git -d <branch-name>`

## References

The most common workflow for this club will likely include the following commands:

```
# get latest changes from main 
git checkout main
git pull

# start work in a new branch
git checkout -b <branch-name>

# save progress locally
git add <file-you-modified>
git commit -m "Meaningful Message about Commit"
```

For more information you can visit our [Github](<TBD>)
