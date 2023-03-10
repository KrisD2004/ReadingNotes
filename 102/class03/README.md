# Revisions and the cloud

## Remote Repositories

To be able to collaborate on Git Projects you would have to interact with Remote Repositories of a project residing online.
All teams can use remote repositories to push info to and pull data from.

*Cloned Repositories*
For Cloned repositories, Git will automactically give the "origin" to the server from which you had cloned and had named "master" to your local branch

*Seeing your remotes*
By running the git remote command, you can view the short names, such as “origin,” of all specified remote handles.

By using git remote -v, you can view all the remote URLs next to their corresponding short names.

WHAT IS GIT?
*Snapshots*
Git is a DVCS that stores data in a file system made up of "snapshots"
Everytime you save a changed version of your project called -COMMMIT- Git creates a "snapshot" of the file and stores a reference to it but if the file hasnt changed, Git only stores a reference to the already stored identical version of it.

*Local Operations*
Git most of time relies on *local operations* because most necessary info can be found in local resources.

*Tracking changes*
Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit

## loss of Data

Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.

*Distributed Version Control*
A Distributed Version Control systems (DVCS) addresses the major vulnerability of the CVS: the server as a single point of failure.

*Centralized Version Control*
The need for collaboration within a developer team on a single file or set of files led to the advent of the Centralized Version Control System (CVCS). This system entails a single server storing all changes and file versions, which can be accessed by various clients

WORKFLOW
*local reop structure*
The local git repo has 3 parts

1. Working Directory: the actual files are there
2. Index-area used for staging
3. head- points to the most recent commit

*Saving Changes*
All files in a working copy of a project file are either in a tracked state or untracked state
Tracked files can be modified, unmodified, or staged
Untacked files werent in the last snapshot and dont currently reside im the staging aera

*The life stages of file status*
First- after youve edited a file, Git flags it as modified because of the changes you had made after the previous changes
sec-- you staged the modified file
thired--you commit staged changes

*check file status*
To determine the state of files, utilize the git status command
EX---- $ git status

## Things i want to know

How does using Git help me become a better software engineer?

Summary:
This topic basically explains how to use all the elements on Git. From how to download it on mulitple op systems.
IT shows you how to setup and Git Repo
THis topic talks about cloning and about when you clone a file you have all the versions from a project
This tells you about the 3 componets of a local repo structure and the life cyle of a file
