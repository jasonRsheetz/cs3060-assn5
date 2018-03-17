# cs3060-assn5
Collaborative resource for class assigment

Hey, git push works!


For my novice mind:

Setup git user name and info stuff(s)  
git config --global user.name "Your Name"  
git config --global user.email "Set to your GitHub noreply email (so github recognizes you, yet you keep personal /login/ information safe"  

Clone the branch  
git clone git@github.com:[ADDRESS OF REPOSITORY]  

Pull latest changes from Master  
git checkout master [or a branch]  
or  
git pull  

Make a branch  
git checkout -b NAMEBRANCH  

Commit changes - before pushing to GitHub  
git commit -a [automatically stage files for commit]  

Push changes to GitHub (perhaps working on a branch)  
git push  

Push a new branch into into GitHub  
git push -u origin NAMEBRANCH  

Perhaps a branch is ready to join Master (assuming: working from current branch)  
git checkout NAMEBRANCH  
git merge master  

Perhaps master needs to join branch  
git checkout master  
git merge NAMEBRANCH  

