#MxOnline
# django-project
Command line instructions

Git global setup
git config --global user.name "Zhifeng  Wang"
git config --global user.email "zhifeng.wang@anu.edu.au"

Create a new repository
git clone https://gitlab.cecs.anu.edu.au/u6068466/rr.git
cd rr
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master

Existing folder
cd existing_folder
git init
git remote add origin https://gitlab.cecs.anu.edu.au/u6068466/rr.git
git add .
git commit -m "Initial commit"
git push -u origin master

Existing Git repository
cd existing_repo
git remote rename origin old-origin
git remote add origin https://gitlab.cecs.anu.edu.au/u6068466/rr.git
git push -u origin --all
git push -u origin --tags
