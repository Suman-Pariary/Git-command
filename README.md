-----------------------------------------------------
//--Configure Git--
git config --global user.name "My Name"
git config --global user.email "someone@email.com"
-----------------------------------------------------
//--To Upload a Folder--
git init
git add .                   //if Folder and if add file only file name with extension
git commit -m "commit message"
git branch -M main         //if branch is master/main see that
git remote add origin <Github link>
git push -u origin main    //if rejected/error go to next part
-----------------------------------------------------
//--Create a new branch and upload
git checkout -b my-new-branch
git add .
git commit -m "Commit in New Branch"
git push -u origin my-new-branch
-----------------------------------------------------
//--If you want to push new changes
git add .
git commit -m "Your commit message here"
git push
-----------------------------------------------------
//--If we want to clone a git repo
git clone <repo-url>
-----------------------------------------------------
