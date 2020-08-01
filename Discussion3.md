# Revisions and The Cloud

**You can work on your repositories you can use your terminal on your computer and make updates and changes directly from it to the website. You do this by copying your link and putting into your terminal to create a clone directly to your desktop. From here you can work on and update your code, then have it update to github.**

## Version Control

Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.

- **Local Version Control**

A Local VCS entails one database on your hard disk that stores changes to files.

-**Centralized Version Control**

This system entails a single server storing all changes and file versions, which can be accessed by various clients.
-**Distributed Version Control**

A Distributed Version Control systems (DVCS) addresses the major vulnerability of the CVS: the server as a single point of failure. If a CVS goes down, collaborators cannot work with each other on a file or save changes and new versions. Also, in the event of corruption of a central database’s hard disk — with the absence of backups — all work will be lost, except for any portions on local machines.
To prevent this type of catastrophic loss, a DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.

## What is Git?
**Snapshots**

Git is a DVCS that stores data in a file system made up of snapshots. Every time you make and save a new version of your project (called a commit) Git creates a snapshot of the file and stores it for reference. If the file has not changed, Git only stores a reference to the already-stored identical version of it.
