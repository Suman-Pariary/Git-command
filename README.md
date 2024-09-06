-----------------------------------------------------
//--Configure Git--
git config --global user.name "My Name"
git config --global user.email "someone@email.com"
-----------------------------------------------------
//--To Upload a Folder--
git init
git add .
git commit -m "commit message"
git branch -M main
git remote add origin <Github link>
git push -u origin main    //if rejected/error go to next part
-----------------------------------------------------
//--Create a new branch and upload
git checkout -b my-new-branch
git add .
git commit -m "Commit in New Branch"
git push -u origin my-new-branch
-----------------------------------------------------
