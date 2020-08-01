# Revisions and The Cloud

**You can work on your repositories you can use your terminal on your computer and make updates and changes directly from it to the website. You do this by copying your link and putting into your terminal to create a clone directly to your desktop. From here you can work on and update your code, then have it update to github.**

## Version Control

Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.

- **Local Version Control**

A Local VCS entails one database on your hard disk that stores changes to files.

- **Centralized Version Control**

This system entails a single server storing all changes and file versions, which can be accessed by various clients.

- **Distributed Version Control**

A Distributed Version Control systems (DVCS) addresses the major vulnerability of the CVS: the server as a single point of failure. If a CVS goes down, collaborators cannot work with each other on a file or save changes and new versions. Also, in the event of corruption of a central database’s hard disk — with the absence of backups — all work will be lost, except for any portions on local machines.
To prevent this type of catastrophic loss, a DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.

## What is Git?
**Snapshots**

Git is a DVCS that stores data in a file system made up of snapshots. Every time you make and save a new version of your project (called a commit) Git creates a snapshot of the file and stores it for reference. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

**Local Operations**

Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.

**Tracking Changes**

Every single change applied to any file or directory is tracked by Git.

**Loss of Data**

Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.

**States**

Files in Git reside in three main stages:

*Commited*

Data is securely stored in a local database

*Modified*

File has been changed but not committed to the database

*Staged*

Flagged a file’s changed version to be committed in the next snapshot

## Clone a respitory

Go to the GitHub repository  you would like to clone. Click on the code button and copy the link for your repository. Open up the terminal on your computer. Navigate to where you would like to save your respitory on your computer. Use git clone command to clone the repository to your computer.

Here is what it can look like when you clone to your computer:

cmboe$ pwd

/mnt/c/Users/cmboe

cmboe$ cd desktop

desktop$ cd projects

projects$ git clone https://github.com/cmboell/learning-journal.git

Cloning into 'learning-journal'...
remote: Enumerating objects: 100, done.
remote: Counting objects: 100% (100/100), done.
remote: Compressing objects: 100% (91/91), done.
remote: Total 100 (delta 44), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (100/100), 26.45 KiB | 139.00 KiB/s, done.
Resolving deltas: 100% (44/44), done.

projects$ ls

hello-world  learning-journal

projects$ cd learning-journal

learning-journal[master]$ ls

Discussion.md  Discussion2.md  Discussion3.md  LICENSE  MarkdownExamples.md  README.md  _config.yml  growthmindset.md

Now that you have it downloaded to your computer you can use the code . command to open up and make changes and modify your repository. After that you can save and update the changes you made. Make sure to document your changes within the terminal. Here are some helpful commands:

git status (check the status of the repository and show the changes that have been made)

git add (add the changes you made to your repository)

git commit -m 'add an explanation of the changes' (explains what you have changed)

git push origin master (shares changes you made with GitHub)


**To read more visit:**https://blog.udemy.com/git-tutorial-a-comprehensive-guide/
[Back To Home Page](/README.md)
