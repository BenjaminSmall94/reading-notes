# Revisions and the Clound

## Version Control Systems

> Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.

### Progression Version Control

1. Local Version Control

    Coders began storing various version control systems on their local harddrive to protect from losses and bugs.

2. Centralized Version Control

    As collaboration grew, this led to the advent of the of a Centralized Version Control system. A single server storing all the various snapshots \(versions\) of a code that could be accessed by multiple clients with various permissions.

3. Distributed Version Control

    The next improvent involving VCS's was the implementation of Distributed Version Control systems. The problem with the centralized version control system is that there was a single point of failure in the server which held all the files. Sure there were likely backups on the system but if the server went down, or was corrupted, it would lead to catastrophic results for the team and their work.

    The DVCS allows developers to mirror or "clone" working repositories onto their computer and make edits and then re-upload the revised files to the central repository. This gives redundancy to protect from server corruption and allows developers to continue work during times were the server or internet may not be working.

## Git and GitHub

Git is a VCS that enables developers to track changes a versions to their code in real time. GitHub is an online resource that allows developers to share their repositories with the world and allows for collaboration with anyone you wish to be able to see your work.

### Add, Commit, Push

 Git and GitHub come with various commands to describe and command actions to be performed in the course of editing and saving versions of your code. The most important are the three Add, Commit, and Push in sequence. These let you choose which files to send to the working branch, fix them to the working branch, and then upload them to the central online repository.