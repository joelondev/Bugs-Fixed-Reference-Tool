//to crosscheck the existing url
git remote -v : 

//to remove the existing expired token url
git remote remove origin 

//adding new token with new url
git remote add origin https://{yourtoken}@github.com/username/repo.git 

//confirm new token url
git remote -v