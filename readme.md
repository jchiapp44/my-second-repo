# Second repository: Julian Chiapperino
## Reviewing Git hub Exercises form coursera module4

### NOTES
First step in creating a new repository through git hub was to access my account. Then I went to repositories, clicked the "+" button and selected new repository on drop down menu.
Once i created a repository, i had to clone that repository to the terminal via: git clone urlofnewrepositorythatgithubprovides which is clearly provided when you click on the repository on git hub wbesite.
Right now i am writing text into the readme.md file, which will be converted into HTML website page once i add and commit the changest to the repository, and then sync the changes to the remote repo available on git hub.
 list can be found here:
- **Input** commands correctly into the terminal, otherwise things will not be executed.
- **Commit** changes to repository, particularly in local repositories, adding changes and then committing them is a crucial series of steps.
- **Verify** changes by executing git status, it also tells you which branch of the repo you are in, if you need to adjust other branches then other commands are necessary.
- **Transfer** information across branches requires: git branch, git checkout (changing of branches), git merge branch when you want to extract the information from a particular branch into current one.
- **Remote** repositories require original linking, which can either be done via git push approach, from local to remote, or git pull, from remote to local. 

In summation, important git commands include:
- 'git init' creates local repo
- 'git status' provides status of repo/s contents
- 'git add filename' just adds one particular file, that was presumably changed, to the staging area, awaiting commit to finlaize it.
- ***'git add -A'*** adds all current modifications to files/repository/s contents to the current branch of a repository's staging area.
- ***'git commit -m "message"'*** adds changes from staging area, waiting queue to the actual repository, creates new version of folder.
- 'git branch' allows you to check names of branches, how many different branches exist in repository.
- ***'git checkout branchname'*** used to switch from branch to branch in a single repository
- ***'git push -u remotename branchname'*** will move all commits from a local repository to a remote repository, you must input the remote repository name along with the branch that you want the changes submitted to.
- ***'git push'*** can be done after the previous command, basically set the above branch of the remote directory as the default location for future changes.
- ***'git pull'*** fetches and merges from git hub. takes contents of remote repository and merges them to the current version of the local repo.
- 'git remote add name url' used to add a git hub remote repo to the local device int he current working directory.
- ***'git clone url'*** is the much much much preferred way of doing the processes described above, in one step, it turns a regular working directory into a repository, by cloning an existing remote repository from git hub and inserting all its contents in that direcotry, thereby making it a functioning local repository.
- 'git remote' used to verify a remote repository was linked to the local repository
- 'git diff' compares differences between working directory and the staging area, commits have not been made at this point, if so, no changes would be reflected.
- 'git diff --staged' reflects differences between staging area and the last commit version of the file
- 'git diff HEAD' working directory vs last commit, anything in staging area that has not yet been committed would be ignored.
- 'git diff branch1 branch2' compare the two different branches of a repository
- 'git log' reveals commit history of repository, you can export this to a text via >> gitlog.txt
- ***'git merge branchname'*** allows for taking of contents in one brnach of repo and inserting them, or copying them to another branch of repo as long as there is not a direct conflict with the different versions. for example if there were committed changes in both branches for one particular file, the merge will not be successful
- ***'git merge --abort'*** used for particular conlficts, that are mentioned above, executed so that conflict resolves or that it no longer exists.

I am adding this line from the remote repository, via git hub website, in order to figure out the 'git pull' command.
