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
alternatively you can link the online repo to your local machine by

git init //to initialize a local repo in current dir
git branch -M main
git add . //add all files in current dir to the staging area so they can be tracked
git commit //to add a check point selectively (?an image of current status of selected files in the repo?)
git remote add "origin"  "web url (https)" or "ssh key"  //Link local repo to online repo. Origin is common naming convention for the remote location.
git remote rm origin //to remove this link if required
git push --set-upstream origin main //create a main branch in the remote repo


//from this point on do not push to main branch

git checkout -b  //checkout to move between new branches, -b "name" of branch to create a new branch locally




 using the following command
git remote add "origin"  "web url (https)" or "ssh key"  //origin is common naming convention for the remote location
MV WK4D3 workshop video
4. tracking changes locally
https://www.youtube.com/watch?v=RGOj5yH7evk&t=467s
git add to add files to the staging area so they can be tracked
git add README.md //for a single file 
or git add .      //(for all files in the repo)
git commit //to add a check point, selectively (?an image of current status of selected files in the repo?)
git commit -m "Message title" -m "Description"
git commit -m "Updated README.md" -m "added some notes on the topic 'Intro to Git'"
git log //to see a history of commits (will show commit hash keys)
git checkout "commit hash" //replace 'commit hash' with the commit hash key to load the saved state of a file
5. tracking changes remotely (the online repo)
MV workshop video WK4D3
https://www.youtube.com/watch?v=RGOj5yH7evk&t=467s
git push
git remote 
Other material
MV workshop video WK4D3
https://app.codingrooms.com/
https://www.youtube.com/watch?v=HfTXHrWMGVY&t=62s