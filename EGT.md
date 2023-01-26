This bug is experienced whenever your token expires and 
you have to enter the git token password every time you 
commit a git repo

//to crosscheck the existing url
git remote -v 

//to remove the existing expired token url
git remote remove origin 

//adding new token with new url
git remote add origin https://{yourtoken}@github.com/username/repo.git 

//confirm new token url
git remote -v