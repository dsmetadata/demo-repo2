#Demo
Intro to Git

#Setup

1. Installing Git, creating a Github account and linking the two

https://docs.github.com/en/get-started/quickstart/set-up-git

https://www.youtube.com/watch?v=HfTXHrWMGVY&t=62s

2. Creating your first online Repository, creating a file within the Repo

https://www.youtube.com/watch?v=RGOj5yH7evk&t=467s

3. Cloning an online repo to your local machine, tracking changes locally

git clone "web url (https)" or "ssh key"

https://www.youtube.com/watch?v=RGOj5yH7evk&t=467s


MV workshop WK4D3
alternatively you can link the online repo to your local machine by typing the following into git bash.

git init //to initialize a local repo in current dir




#Add, Track, Commit & Push

once you have initialized a local repo as shown above, type the following into git bash.


git branch -M main

git add . //add all files in current dir to the staging area so they can be tracked.
git add "filename" //for a single file 

git commit //to add a check point selectively (?an image of current status of selected files in the repo?)
git commit -m "Message title" -m "Description"

git remote add "origin"  "web url (https)" or "ssh key"  //Link local repo to online repo. Origin is common naming convention for the remote location.

git push --set-upstream origin main //create a main branch in the remote repo and push to main. authentication may be required

**Additional information**
git remote rm origin //to remove this link if required

git status //check status of current branch

git pull origin "branchName" // Grabs contents of the online version of that branch and adds it to your current branch


//from this point on do not push to main branch




#New Branches

git checkout -b  "name" //checkout to move between new branches, -b "name" of branch to create a new branch locally

git branch //print current branch and list of available branches (local)

git log //to see a history of commits (will show commit hash keys)


#Merge Branches

from the code tab in github, select branches

select New pull request from the branch you wish to pull from

**Important Step**
select the branch you are pulling to (below the code tab and the header 'Open a pull request'
there will be an arrow pointing from the branch you are pulling from to the one you are pulling to)
ensure the branch you are pulling to is correct.

where applicable add a Reviewer by selecting the cog/settings wheel on the right

select create pull request //collaborators will get an email with a link to review this request
the email will send collaborators to the pull request tab, alternatively if you navigate directly to the pull requests tab next to 'Code' 'Issues', you should be able to see the pull request.

select merge pull request & confirm merge //comments/reviews can be added before finalizing the merge

#Delete Branch
**Optional**
git branch - d "branch name"

#Add Collaborators
head over to the settings page of the repo and select collaborators and add people
once the collaborator accepts the invite they will be able to amend any branch in the repo






#Other material

MV workshop video WK4D3

https://app.codingrooms.com/

https://www.youtube.com/watch?v=HfTXHrWMGVY&t=62s