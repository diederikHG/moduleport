# Howto setup

1. Go to a folder on your pc where you want your module workspace folder
2. right click in the folder and open Git Bash or open Git Bash and cd to the directory
3. clone the repo: ``git clone https://github.com/diederikHG/moduleport.git``
4. the git repo is cloned!
5. add your github account as local user: ``git config user.email "diederik.depourcq.j2625@student.hogent.be"``


# Before you start making changes

1. have Git bash in the root of your git repo
2. check if there were remote changes by fetching the remote information first: ``git fetch``
3. now that we have the remote information, check if there were changes: ``git status``
4. if your master is behind, we have to pull the updates: ``git pull``
5. if we check now, our master branch is up to date: ``git status``
6. now we can start working on the repo


## After you made changes
1. have Git bash in the root of your git repo
2. after you've made the changes, check again for updates: ``git fetch`` & ``git status``
3. depending on the output follow the first section if there were remote changes and follow the second section if there weren't

## There were remote changes while you were working

1. have Git bash in the root of your git repo
2. select all files that you changed and add them (-A includes the deletion of deleted files): ``git add -A .``
3. commit the local changes with a relevant message: ``git commit -m "Update readme with commit instructions"``
4. merge the local changes with the remote changes: ``git merge originT/master``
5. if you get a merge conflict, check which files are affected: ``git status``
6. open the affected files, check and correct (don't forget to remove unnecessary comments) the merged content where there are git comments. Save the file.
7. add the corrected file(s) agin (in my case README.MD): ``git add README.md``
8. commit the files: ``git commit -m "Update readme with merge resolve"``
9. Push the changes ``git push``
10. And you're done :)


## There were NO remote changes while you were working

1. have Git bash in the root of your git repo
2. select all files that you changed and add them (-A includes the deletion of deleted files): ``git add -A .``
3. commit the local changes with a relevant message: ``git commit -m "Update readme with commit instructions"``
4. Push them: ``git push``
5. When prompted, give your password
6. And you're done :)
