git init -- init git in folder
git config --global user.name "name" -- add user name global in git
git config --global user.email "name" -- add user email global in git
git add Readme.txt -- add file in commit
git add mainModule.py -- add file in commit
git commit -m 'init commit' -- add commit in master
git status  -- check changes and commits
git log -- check history commits
git diff -- check diff between commits
tree .git -- threefolder
git remote add origin https://github.com/KronoKuro/gitExperiment.git 
--add remote repos
git remote -- check had remote repos
git push origin master -- push to master to remote repos
git pull origin master -- pull changes from master
git checkout a10ecd66fdd13d91b42e1a3b5ae48033eccb9e43 -- go to commit a10ecd66fdd13d91b42e1a3b5ae48033eccb9e43
git show a10ecd66fdd13d91b42e1a3b5ae48033eccb9e43 -- check a10ecd66fdd13d91b42e1a3b5ae48033eccb9e43 commit
git branch --show active branch 
git branch -a --show all active branch 
git branch second -- create branch with name second
git checkout second -- go to branch second
git merge second -m 'merge second into master -- merge changes
