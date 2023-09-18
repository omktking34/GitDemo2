# Git Demo 2

Input Text of Git Access

# This is how to access another remote repository with git: 

*1) git remote add origin git@github.com:omktking34/GitDemo

*2) git push-- to setup remote for new file 

*3) git remote -v  -- to access the remote setup 

*4) git push origin HEAD:main -- to access another remote file

*5) git commit -m "insert why text"

# How to Navigate with Git access in Github?

# navigate to your repository
cd /path/to/your/repository

# create a new file
echo "Hello, World!" > example.txt

# add your new file to the staging area
git add example.txt

# now you can commit your changes with a message
git commit -m "Add example.txt"

# finally, you can push your changes to the remote repository
git push origin master 
or git push origin HEAD:(name of branch)
-->

<!-- TODO Access to the branches
*1) git branch  -- access current branch

*2) git checkout master -- access another branch 

*3) git checkout feature-readme-instructions 
TODO-->

