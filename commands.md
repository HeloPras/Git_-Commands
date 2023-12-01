
General Git Commands:

git clone - this helps to clone the repo you want in the github 
syntax:
    git clone ssh or https (you will find this inthe code menu which is in green color, you just copy and paste the ssh key or https url in place of ssh or https given in the syntax)

git init - connects the local repo with git hub
syntax:
    git init

git status - shows all status of all the current file in the folder
syntax:
    git status

git add - adds the untracked files to add category so that we can commit
syntax:
    git add filename (note we can use "." to add all the files)

git commit - we commit the changes we made in the file in the local machine 
syntax: 
    git commit filename (note we can use "." to commit all the files)


git push - to push all the commited file into the github
syntax:
    git push origin main or master (this varies as per the name you set)

git remote add origin - this command is to connect the newly created repo in github with the local repo  you are working on
syntax:
    git remote add origin ssh (you will find the ssh when you create a new repo in the github, copy the paste the ssh in place of ssh in the syntax)

Git Branch Commands:


git branch - shows all the existing branches and the one we are currently in.
syntax: git branch

to create new branch
syntax:
    git branch -b branch_name

git checkout - this is to swap between the branches in your local machine
syntax: 
    git checkout branch_name

git merge - to merge the seconday branches into the main one
syntax:
    git merge secondary_branch_name (note you have to be in the brach, in which you want the secondary branch to merge into
    
    for example:
    
    if my main branch name is master, and i want other secondary branches to get merged into my main branch
    i have to be in the main branch ie. master using the git command (git checkout master)
    )

to delete the existing branch
syntax:
    git branch -d branch_name

git diff - to compare the different branches, to look what changes are there in different branches
syntax:
    git diff branch_name

git pull - to pull the main branch after merging into the main, after we use this command we can see the updated main in the local machine
syntax:
    git pull origin master or main (as per the name of your primary branch in github)



