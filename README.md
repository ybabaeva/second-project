# **How to work with git**
0. Configure git
 git config --list
 cat ~/.gitconfig
 git config --global user.name "Yulia Babaeva"
 git config --global user.email julia.khokhlunova@gmail.com


1. _Initialize repository_
''' git init
'''
2. _Add files to repository_
''' git add README.md
'''
3. _Commit the changes_
''' git commit -m 'Useful message'
'''
4. _Link local and remote repositories_
'''  git remote add origin ...
'''
5. _Push the changes to remote repository_
''' git push -u origin master
'''
 git push

**To get the status**
''' git status
'''

Hash - is unique commit identifier

** To check git log**
git log
git log --oneline