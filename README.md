# Git notes for local work  
git intit : initialize current folder as a git repository
git clone <URL>: brings the git repo from <URL> : brings the git repo from <URL> to current folder 
git status : tells us what we need to know about our repository

git add <FILE> :adds <FILE> to the the staging area
git commit: open a text eitor to write commit message 
    git commit -m "MESSAGE" :wrutes MESSAGES as a commit without a text editor 
git log : shows  the log (hostory) of our commits  
  git log --oneline : shows the shoter online commit 

# working with remotes 
    
git diff : compareb current uncommited state with the last know git state 
gi diff --staged : runs git diff between the stagin area an the last know state 
git diff HEAD ~3<NUMBER>: compare HEAD with commit <NUMBER> ago ( relative)
git diff <HASH>: compares HEAD with the commit in <HASH>
git restore --source <HASH OR HEAD~> <FILE> restore file to <HASH OR HEAD~ >
- git checkout main : gobak to main 
- git switch main : go back to main 
- git remote add <NAME> <URL>
- git remote rm 
- git remote push 
- git remote -v 

