"# create-new-repository-using-cmd" 

create new repository:>//'''''''''

echo "# create-new-repository-using-cmd" >> README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin https://github.com/subincarter/create-new-repository-using-cmd.git

git push -u origin master



commit existing repository:...........

git init

git add .

git commit -m "Initial commit"

git remote add origin <project url>
  
git push -f origin master

