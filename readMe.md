# Git/GitHub Checklist (Team workflow)

## One person on each team

1. Create a new repo on gitHub
2. clone it to your local computer
3. Create the base files for your application (if you are creating an express app, run the generator and follow that checklist before add/commit/pushing to gitHub)
4. Add each team member as a collaborator to the repo on GitHub

## Each person on the team

1. clone the repo (do NOT fork it)
2. create your own branch git checkout -b YOURBRANCHNAME
3. When you are working on your own branch:
   1. `git add -A` (or the appropriate command to commit the files you intend to commit)
   2. `git commit -m "commit message"`
   3. `git pull origin master` This step allows you to retrieve any new code that has been added to master by your teammates. To avoid large, difficult merge conflicts, do this step fairly frequently
   4. Fix any merge conflicts
   5. `git push origin YOURBRANCHNAME`
4. If the feature is done and tested and and all of the above steps have been followed:
  1. Go to GitHub and submit a pull request from your branch to master
  2. Wait for team members to approve the pull request and merge it into master



Collapse 
