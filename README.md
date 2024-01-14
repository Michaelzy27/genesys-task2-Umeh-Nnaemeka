# genesys-task2-Umeh-Nnaemeka
### Version Control:
Version control can be explained as the use of technology to track changes made a user or users in a project/codebase. It allows someone to backtrack and get previous versions of a project as well as determine who made changes and also the time the chnages wee made. It allows or easy teamwork and problem solving as users are able to quickly identify problems and go back to previous versions to solve them.

### Difference between git and github:
Git is a version control used to track changes made on a project by a developer and access previous versions of a project when needed.  
Github is a a web app or pltform that houses git repositories ade by developers using git and also allows for easy collaboration between diffent devlopers on a project by providing extra functionalities.

### Github alternatives:
* Mercurial
* Helix core
* Bazaar

### Difference between git fetch and git pull:
Git fecth only gets changes from the remote repository wiouth merging it into your working branch. It basicaly allows you to view the changes.  
Git pull gets the changes from the remote repository and merges them into your branch automatically

### Git rebase:
Git rebase in simply terms is a command that is used to align new changes made in a branch in front of the updaed main branch. When git rebase is used, the commits made in the new branch and simply put directly into the main branch without a merge happening between the two branches which would bring about a new commit. This would make the commi history cleaner as the commits all appear linear.  
The command for git rebase is :  
    git rebase *my_branch*  
**(note: 'my_branch' is the name of the new branch)**

### Git cherry pick:
Git cherry pick is used to move one or more specific commits from one branch to another. This can be used when the developer wants to pull a specific change from a branch wothout pulling all changes. He/she speicifies the particular commit or commits he wants out of all and he commits are added to his branch using the commit ID.  
The command for git cherry pick is:  
    git cherry-pick *commit_id*  
**(note: 'commit_id' is the id of the commit needed which is always a number eg git cherry-pick 843842)**