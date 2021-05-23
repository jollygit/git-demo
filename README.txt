How to add new file to remote repository

1) Add the file in the curent directory
2) Open git bash and go to the current directory
3) git status
4) git add <<filename>>
5) git commit -m "Committing a new file PYTHON requirements"

6) git push origin master

For First time connect ..use below commands after step 5
 $ git remote add origin https://github.com/jollygit/git-demo.git
 # Sets the new remote
 $ git remote -v
 # Verifies the new remote URL