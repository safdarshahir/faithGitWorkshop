What is Git?

Free and open source version control system


What is Version Control?

The management of changes to documents, computer programs, large web sites
and other collection of information.


------

Terms
    
    Directory -> Folder.

    Terminal or command line -> Interface for text commands.

    CLI -> Command Line Interface.

    cd -> change directory.

    Code Editor -> word processor for writing code.

    Repository -> Project or folder where your project is
                    kept.

    GitHub -> A website to host your repositories online.

------

Git Commands 

clone : Bring a repository that is hosted somewhere like GitHub 
        into a folder on your local machine.
        git clone <url>

add   : Track your files and changes in the Git.
        git add .

commit : Save your files to Git.
        git commit <options>

push : Upload Git commits to a remote repository like GitHub
        eg: git push <options>
    
pull : Download changes from repo to your local machine.
        eg: git pull <options>

status : Check to see which files are being tracked or need to be
         commited.
         eg: git status 

init : Use this command inside of your project to turn it into a Git repo.

Top git commands;

    git init [repo-name] : initilizing new repo.
    git clone [url] : Obtaining a repository from an existing url.
    git add file : add a file to staging area.
    git commit -m "commit message" : save the file permanently in version history.
    git branch : list all the local branches in the current repo.
    git branch [branch-name] : Creates a new branch.
    git checkout [branch-name]: Used to Switch from one branch to another.
    git checkout -b [branch-name] : Creates a new branch and switches to it.
    git remote add [remote-server-link] : used to connect your local repo to remote server.
    git push [variable-name] master/main : Sends committed changes of master/main to remote repo.
    git pull [repository-link]  : Retrieves and merges changes of remote server to your working directory.
    git diff :  Shows the file differences which are not yet staged.
    git merge [branch-name]: To merge the branch to current branch to working directory.
    git status : lists all the files that have to be commited.
     








