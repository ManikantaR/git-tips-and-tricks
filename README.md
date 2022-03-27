# git-tips-and-tricks
Git commands, Tips and Tricks 

# View git log as graph and comments in single line 
git log --graph --online --decorate 


# create Git alias
git config -g alias.<shortletter> "ex:commit -m"

# Git Bist to walkthough commits and identify bad commit 
git bisect start
git bisect good ####
git biest bad

# squash git commits while merging 
--interactive will start merge interatively 
git rebase main --interactive 

pick commitno 
 --fixup  // to use single message when squashing instead of merging all messages from previous commits 
 --squash // use squash flag while commits  
git rebase -i  --autosquash

 
 # update last commit mesage or files using amend
 
 git commit --amend -m ""
 
 git add .
 git commit --amend --no-edit // add files to last commit
 
 # Git hooks
 use Husky javascript library to use git hooks.
 
 # Goto previous branch - if you had recently switched out of branch and forgot brnach name, you could tp previous branch
 git checkout - 
  
