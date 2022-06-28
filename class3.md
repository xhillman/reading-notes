# Intro to Git

## What is version control?

Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes.

Many years ago, most developers used a Local Version Control System (LVCS) which stored changed on your hard disk.

Then came Centralized Version Control Systems (CVCS) which allowed multiple parties to store and see changes on a single database server.

Today we land at Decentralized Version Control Systems (DVCS) which prevents the problem of a single point of failure that can come with an CVCS. 
A DVCS allows clients to make cloned copies of database files so that they can be accessed even if something were to happen to the main server. It also
allows the main servier to be restored in the event of corruption.

### What is Git?

Git is a DVCS that stores data in a file system made up of snapshots, or **commits** which are created every time a file is saved. Git is useful for
tracking changes in files as it saves a new snapshot that can be referenced and reverted to later.

#### The 3 States of Git

**Committed** - Files are securely stored in a local database.

**Modified** - file has been changed but not committed to the database.

**Staged** - Flagged a file’s changed version to be committed in the next snapshot.

## Setting Up a Git Repo

### Importing

In the Terminal, follow these steps:

- Switch to the target project’s directory

> `$ cd test (cd = change directory)`

- Use the git init command

> `$ git init`

- To start tracking these repository files, perform an initial commit by typing the following:

> `$ git add *.c`
> `$ git add LICENSE`
> `$ git commit -m “any message here”`
