# A03
Hello! Welcome to my guide on how to use webstorm, git, and github.
For convenience sake, I'm going to split this tutorial into categories.

1)Getting Started Setup-

First things first, Webstorm is where you are going to be doing most of your development for this class.
You can find webstorm at https://www.jetbrains.com/webstorm/ .
After this, you should download <b>git</b> at https://git-scm.com/downloads .
Finish the installation for these and then go into webstorm, you'll want to set up git as your version control system.
To do this, do (Ctr+Alt+S) > Version Control > Git.
After this, you should link your <b>github</b> account to Webstorm.
If you do not have that, create a github account at https://github.com/ .
Github can be linked in the same place as git, (Ctrl + Alt + S) > Version Control > Github.

2)Your First File-

Setting up your first file is actually quite easy. Go to "Create New Project" Give the project a name and press create. This creates a new project and puts you into the project viewer. Create a new file in webstorm using File > New > whatever type of file you'd want.
After your file is ready to go, you can create a git repository for using github and put your new file up on there. Go to VCS > Create Git Repository or go to Git -> Commit if you already have a repository.
If you dont already have a repository, adding the project to github is simple. Just go to Git > Share project on Github and fill out the prompt there.

3)Using Git and GitHub

Learning how to use Git is vital to learning version control and project management. Now that you've installed git, run the following command to make sure things are correct, type '<b>git</b> --version' if you see a version over 2.0.0 you should be good. Some things to know about git and github are basic commands for using version control are cd, clone, add, commit, push and pull.
cd in git stands for "change directory", you'll want to be sure your in the correct location using cd. pwd shows your working directory and that's used to ensure you know where you are and what your sending around.
you can copy your github url and <b>clone</b> the repo to your local machine using 'git clone https://github.com/user/repo.git repo'
when you have a file you want to <b>push</b> using git bash, you can use git add filename.md to make git aware of the file, 'git commit -m "commit name"' to <b>commit</b> the file to the repo, and then 'git push origin master' to push it to the main <b>branch</b>.
'git pull' works the same way as 'git push', but for the opposite way around. instead of going from your local machine to the <b>remote</b> repository, it will go from the <b>repository</b> and <b>pull</b> it to your local machine.
If all has gone well, you will now know how to push a file onto github without using webstorm if you needed to do something like that.
I think its important to understand how git and git bash works in order to not depend on just using WebStorm for file management.

4)Other Helpful commands
If you have multiple <b>branches</b> and need to interact with different versions and content from your various branches, you can use 'git fetch' to get things from other branches to have greater control over your branches.
If you need to bring two different branches together, you can use 'git merge' to merge two branches together, just make sure they are not duplicate branches, or else you may encounter a merge conflict.
If you need to create a local repository using bash, 'git init' is a good command for that.
If you need to see the list of changed files, you can use 'git status'.

Thanks for reading! Let me know if you think anything can be addressed better or if this general guide was good. This is in no means an in depth guide and is just meant to be an introduction to using git, github, and webstorm. Here is a glossary of terms used in this guide:

*Branch* - a "lightweight movable pointer to a commit" With the default being master, they help you organize your workflow by letting you sort your commits to different branches. Using 'git branch' shows existing branches in your repository.<br>

*Clone* - takes an repository and puts its contents into a new directory. 'git clone url' clones a repository, coping all its files, branches and commits.<br>

*Commit* - similar to a snapshot of a repository, a commit includes new code, metadata for the time and date, and a message typically containing context for changes. 'git commit -m "message"' creates a commit.<br>

*Fetch* - fetch gets content from another repository and allows you to interact with other branches differently from a merge.<br>

*GIT* - a version control system, git stores snapshots of your project over time through commits, which are sorted in branches in repositories. Allowing you to easily keep your project up to date and optimize workflow.<br>

*Github* - A website which hosts git based projects, where your projects get sent to when using git.<br>

*Merge* - merging brings the history of branches together, it takes the work and content of one branch and merges it into another.<br>

*Merge Conflict* - when two files have similar changes and git can not figure out what to merge.<br>

*Push* - takes content from your local machine and pushes it onto github. 'git push origin master' for example pushes to the master branch.<br>

*Pull* - the inverse of push, it pulls content from github and pulls it onto your local machine.<br>

*Remote* - a collective repository for code that's hosted on github, 'git clone', 'git status', 'git push' and 'git pull' interact with the remote.<br>

*Repository* - the core element of github. The place where your files and content that you will be managing and updating lie.<br>

References:<br>
https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell<br>
https://github.com/git-guides/git-clone<br>
https://git-scm.com/docs/git-fetch<br>
https://www.git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F<br>
https://github.com/git-guides/git-remote<br>
https://git-scm.com/docs/git-fetch<br>
https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html<br>
<br>

