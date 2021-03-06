# Section 3

### To Setup GIT
Get a Github account from [Github](Github.com)
Download and install `git` onto your computer
Set up `git` with your `user name` and `email`

Once `git` is setup you can clone repository onto your local machine.

Then we can setup your own branch using the comamnd line in your Terminal:

`git checkout -b <branch name>`

Then you will be able to work within your branch.

### Concept of Branching
We branch in Git and Github to protect our work and to protect work of others. With branching we can work collaboratively on one project and if we are working on the same material we can request a review and the person who review the quality of the code can push the correct code into the master branch. 

### Avoiding the merge conflict
We avoid merge conflicts by having someone review any request to push to the master branch. 

Github makes it easy for us to review the merge conflicts by telling us what file has the conflict.

We can use the web editor to open the file and the place where <<<<<< is marked is usually where the conflict emerges.  

We can remove these conflicts by deleting what we don't need added to the merge.

Once the conflict is resolved we are allowed to merge.



### Forking vs Cloning  
**Forking:** When you fork a repository you are copying the entire repository to your github account.  People use to make invoke a change to their repository or to use is as a starting point for their project.

To fork a repository go to that repository in Github. In the upper right corner click the fork image and you will copy the repository onto your account.

![Fork](Fork.png "Fork Icon")

Check your repositories and you should see the forked repository on your Github account.

**Cloning:** When you clone a repository you are copying the repository onto your local machine. 

**To clone a repository from Github:**
1. Click the Clone or download
2. You have a choice to either download the repository to a zip file or you can clone using a password protected SSH Key
3. If you are cloning with SSH, ensure your public key is enabled and loaded.
4. Open your Terminal and change to the directory you want to clone your repository
5. Use command `git clone <name of repository>`
6. The repository and the alloted filed should be on your local machine

### Pull Request
**Pull Request:** We make pull request to make changes and/or collobrate to a repository.

To create a pull a request:

**In Github**: From repository click `new pull request `

Under `compare master` select your branch add a title but a title is already there based on your commit message.

Here we can also add a reviewer on the right side column.

If a reviewer is added they will be able to fix Merge Conflicts and review the code before approval.

Once approved, the changes can be merged into the master.

This is a great safety protocol to ensure quality code is going into the master branch that will not break websites and applications.

**In your Terminal**
Run command `git request-pull [-p] <start> <url> [<end>]`

`-p <start> <url> <end>` is optional where `-p` is the patch text in output, `<start>` is the commit to start at, `<url>` is the url of the repository, and `[<end>]` is commit to end at.

### Adding a Collaborator to a Github Repository
To add a collaborator to a GitHub Repo:
1. Go to **Settings**
![Settings](Settings.PNG "Setting")
2. On the left hand side select **Collaborators**

![Collaborators](collab.PNG "Collaborators")

3. You can add a collaborator by adding username, full name, or e-mail address
![Add](add.PNG "Add")


## Other Sections:
### Section 1
[Section 1](section1.md)

## Section 2
[Section 2](Section2.md)

## Authors
*Collaborative Effort* by:
1. **Afreen Farhana Uddin**
2. **Aman Trivedi**
3. **Wismy Seide**
