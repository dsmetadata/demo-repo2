#Demo
Intro to Git
1. Installing Git, creating a Github account and linking the two
https://docs.github.com/en/get-started/quickstart/set-up-git
https://www.youtube.com/watch?v=HfTXHrWMGVY&t=62s
2. Creating your first online Repository, creating a file within the Repo
https://www.youtube.com/watch?v=RGOj5yH7evk&t=467s
3. Cloning an online repo to your local machine, tracking changes locally
git clone "web url (https)" or "ssh key"
https://www.youtube.com/watch?v=RGOj5yH7evk&t=467s


MV workshop WK4D3
alternatively you can link the online repo to your local machine with the following steps

git init //to initialize a local repo in current dir

git branch -M main

git add . //add all files in current dir to the staging area so they can be tracked.
git add "filename" //for a single file 

git commit //to add a check point selectively (?an image of current status of selected files in the repo?)
git commit -m "Message title" -m "Description"

git remote add "origin"  "web url (https)" or "ssh key"  //Link local repo to online repo. Origin is common naming convention for the remote location.

git remote rm origin //to remove this link if required

git push --set-upstream origin main //create a main branch in the remote repo


//from this point on do not push to main branch

git checkout -b  "name" //checkout to move between new branches, -b "name" of branch to create a new branch locally


git branch //print current branch and list of available branches (local)

git log //to see a history of commits (will show commit hash keys)



Other material
MV workshop video WK4D3
https://app.codingrooms.com/
https://www.youtube.com/watch?v=HfTXHrWMGVY&t=62s