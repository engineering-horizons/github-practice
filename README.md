# Practice Github Commands

This is not a comprehensive introduction to git. There are a lot of great resources out there of how to use git. This repo is intended to give members a low stress sandbox where they can practice commonly used git commands


## What Should You Do?



Practice!


### Commits
1. **Clone the repository**
  -  Before you can make any edits, you first have to clone the repository
  -  `git clone https://github.com/engineering-horizons/github-practice.git`
2. **Create a file!**
  -  You can do this through vscode or the terminal. Its up to you!
  -  Once you have created a new file, you have to "stage" those changes.
  -  `git add 'file-name'`
     - **NOTE**: you CAN use `git add .` to add everything you have modified in 1 command. We recommend NOT doing this because this might add any system files or pre compiled files. 
3. **Push your changes to `main`!**
  -  After you make a commit, these changes are still only in effect on your local clone of the repository. To add these changes to the remote repository, you have to push.
  - `git push`
     -  **NOTE**: if someone else has made changes and pushed them before you, you might have to `git pull` to update your local copy of the repository before you can push!


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
