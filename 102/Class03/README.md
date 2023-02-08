# Revision and the cloud Article notes

git stash- temporarily removes changes & hide them

git stash apply- command to retrieve hidden changes

**Remote Repositories** </br>
To collaborate on git projects you must interact with remote repositories or some verison of a prject online/ network. You can give permission to read or write to multiple reportories. Teams can push remote reportories info to and pull data.

**Clone Repositories** </br>
Git will automatically give the name "orgin" to the server.

**Seeing Your Remotes** </br>
git remote- can viewthe short name such as orgin of all remote handles

git remote -v - to view all remote url's

$ cd example

$ git remote -v

remote1 https://gfdhfmh/remote1/example (fetch)

remote1 https://gicfcmhc,/remote1/example (push)

**Adding Remotes** </br>
To create a new remote Git repository with a short name,

git remote add shortname url

Fetching
Fetching pulls data that you don’t have from a remote project.

git fetch [remote-name]

**Pushing**</br>
To **push** your changes “upstream” for sharing, use 👉🏽 git push [remote-name][branch-name]

**Renaming/Removing Remotes**</br>
git remote rename js jane </br>$ git remote</br> origin </br>
jane

**Remove** </br>
$ git remote rm jane
$ git remote

origin
