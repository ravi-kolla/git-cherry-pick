# git-cherry-pick
demo for cherry pick specific commit

```
git clone your-repo
cd your-repo
git checkout your-branch-with-changes
git pull //to get all your commits to local
git checkout your-branch-to-add-specific-commits
git pull //to make sure branch is upto date
git cherry-pick commit-id
git push //commits the picked commit to the target branch
```
