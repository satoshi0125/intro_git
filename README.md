# contents
git config --global

1. this is git practice
2. "git add"=>send staging area
3. "git commit"=>send localrepository
4. "git add -A"
5. "git commit -m "message""
6. "git branch"=> check branch status
7. "git checkout -b branch_new_name"=>make new_branch
8. "git checkout branch_name"=>change or swich branch_name
9. "git merge branch_name"=> connect two branches
10. "git push"=>send localbranch to Github or bitbacket.etc...
11. "git clone [repositoryURL]  [directory]"=>copy All in the repository
12. difference push and commit for git https://teratail.com/questions/79531
13. git add => git commit -m "message" => git push

# or create a new repository on the command line
echo "# satoshi0125.github.io" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/satoshi0125/satoshi0125.github.io.git
git push -u origin master

# or push an existing repository from the command line
git remote add origin https://github.com/satoshi0125/satoshi0125.github.io.git
git push -u origin master

# or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
