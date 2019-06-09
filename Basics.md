# Version Control System (VCS)
- Helps developers in maintaining history of their work.
- **Functions of VCS**
	- Developers can work simultaneously.
	- Can't overwrite each other's changes.
	- Maintains history of each version.
- **Types of VCS**
	- Centralized Version Control System
	- Distributed/Decentralized Version Control System
# Distributed Version Control System
- Developers can take snapshot of latest work.
- Fully copy the work.
- In case of server failure the repository can be copied from the users for restorartion.
- Work can be done offline.
- Commit changes, creating branch, viewing logs and other operations can be done offline.
- Network connection is needed only when publishing of work is needed.
# Advantages of Git
- It is free and open source. It's source code is available freely to be downloaded and modified.
- As network connection is not needed for each operation, it is fast and stores the data on client's server in compressed format so it is small.
- As data is stored at multiple places, chances of loosing data is less.
- Use Secure Hash Funchion (SHA1) to name and identify objects. So it's secure.
- No need of powerful hardware.
- Easier Branching.
# DVCS Terminologies.
## Local Repository
- It is a private repository for the developers and separate from the main repository.
- Once the commit is done then only the changes become part of main repository.
## Working Directory and Staging Area or Index
- Basic worklow of git:
	- Modification of file in working directory.
	- Addition of file in staging area.
	- Commit operation moves the files from staging area.
	- Push operation stores the changes permanently to the Git repository.
## Blobs
- Binary Large Objects. It is the representation of every version of a file.
## Trees
- It represents a directory.
- It contains Blobs and other directories.
## Commits
- Hold the current state of the repository.
- Every commit acts as a node of linked list and has a pointer to the parent node of the list.
- Using a commit we can see the history of the commit.
- When two branches are merged the reultant commit will have more than one parent.
## Branches
- Create a separate line of development. They are created to work on new features.
- After completing the features the new branch is merged back with the master branch.
- Every branch has a head which refers to the latest commit.
## Tags
- Meaningful name to a version in the repository.
- Tags are immutable i.e. tag is a branch which nobody inteds to modify.
## Clone
- Creates an instance of repository. Mirrors the complete repository.
- Netwonking is involved only when synchronization is 
