# Repository : 

A repository is like a folder for a project. Project's repository contains all of the project's files and stores each file's revision history. The file history is stored as a snapshot in time called commits.

# Clone:

**Clone** is used to create a local copy of a project that already eists remotely. Clone copies all the project files, branches and history.

### Example:
 
	* git clone <repo url>
	* git clone https://github.com/wseide/miniproject1.git

# Fork:

**Fork** is a copy of repository that developer manage and changes without affecting the original repository. The difference between fork and clone is that fork copy resides in github but clone copy resides in local machine

### Example:
 
	* On the github navigate to the repository
	* In the top right corner of the page click Fork

 # Branch:

**Branch** is separate from master which enables users to work locally and change made on the branch does not affect the master brach. Once all the changes in braches checked it can be added to the master and updated.

### Example:

	git checkout -b <branchname>
	git checkout -b Afreen

# Commit:

**Commit** saves the snapshot to the project history and completes the change tracking process. Anything that is changed will be staged by adding **git add** and it will become part of snapshot with git commit

### Example:

	git commit -m "Definition of commit added"
=======
A repository is like a folder for a project. Project's repository contains all of the project's files and stores each file's revision history. The file history is stored as a snapshot in time called commits.
