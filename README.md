# Howto setup

1. Go to a folder on your pc where you want your module workspace folder
2. right click in the folder and open Git Bash or open Git Bash and cd to the directory
3. clone the repo: ``git clone https://github.com/diederikHG/moduleport.git``
4. the git repo is cloned!
5. add your github account as local user: ``git config user.email "diederik.depourcq.j2625@student.hogent.be"``


1. check if there were remote changes by fetching the remote information first: ``git fetch``
2. now that we have the remote information, check if there were changes: ``git status``
3. if your master is behind, we have to pull the updates: ``git pull``
4. if we check now, our master branch is up to date: ``git status``
5. now we can start working on the repo
6. when you've made the changes, check again for updates
