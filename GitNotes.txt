
### Steps to Clone to Local Computer, Make File Changes, Push Back to Github

tip - put all repos in Desktop so can see visually
git clone url.git  --to make local copy of your or other's repo
git remote -v  --to see your remote repos in GitBash type
git status  --to see status of files in that directory (tracked or untracked)
git add .  --to stage files on local comp for committing
git commit -m "message" --to commit files to be pushed to github with message description of commit files
git commit  --to commit files to be pushed to github without message
git push origin master  --to push local master to remote origin
---> enter github username/pass, then refresh github to see changes


### to copy your repo to your local computer
git init -- initializes a local git repo in home directory
git remote add origin [url] -- gets repo from location you specify (repo's url is url of the repo's page on github)

### to fork someone else's repo
click the fork button on the repo's github page
clone it to your computer via git:
git clone [url] -- puts a copy of the repo on your local computer 
(puts it into current working directory)


### ADDING FILES TO INDEX
- if you add new files to a local repo under version control
- tell Git that they need to be tracked by using add command
- do this before committing
git add -- adds all new files
git add -u -- updates tracking for files that changed names or were deleted
git add -A -- does both of the previous


### COMMITTING TO LOCAL REPO
- only updates local repo (no changes to github)
git commit -m "message"  -- put description of what you did in the message


### PUSHING TO GITHUB
- updating changes to github
git push -- pushes all changes to remote directory on github


### BRANCHES
- useful when working project with a version that's being used by many people
- you may not want to edit that version
- you can create a branch which is another version of same directory
git checkout -b branchname -- creates new version of branch you tell it to
git branch -- tells you what branch you're on at the moment
git checkout master -- switches you back to the master branch


### PULL REQUESTS
this is how to request that your changes be merged with the original file (branch)
this is done in github only - cannot be done in git

### RESOURCES
git documentation  http://git.scm.com/doc
github help https://help.github.com
Google/Stack Overflow are great for help with GitHub