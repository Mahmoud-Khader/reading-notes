# Git

it's software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows (thousands of parallel branches running on different systems)

### snapshots

Git is a DVCS that stores data in a file system made up of snapshots.

### Local Operations

Git mostly relies on local operations because most necessary information can be found in local resources. 

### Tracking Changes

Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.

### Loss of Data

Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.

### States

Files in Git can reside in three main states: committed, modified and staged.

> Committed

Data is securely stored in a local database

> Modified

File has been changed but not committed to the database

> Staged

Flagged a file’s changed version to be committed in the next snapshot
![snapshot](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)

## Workflow

### Local Repository Structure
The local Git repository has three components:

1. Working Directory: The actual files reside here.
2. Index: The area used for staging
3. Head: Points to the most recent commit
![LRS](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)

### The Life Cycle of File Status
1. After you edit a file, Git flags it as modified because of changes made after the previous commit.
2. You stage the modified file.
3. Then, you commit staged changes.
![Life cyrcle](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)
### Check File Status
To determine the state of files, utilize the git status command:

$ git status

### Tracking and Staging a New File
**Single File**

Track one file only by using the following format:

git add filename
**All Files**

Track all files in a repository by using the following command:

$ git add *
*After using these commands, files are tracked and staged for committing.

After adding a new file called EXAMPLE, you would see information regarding changes to be committed when using the git status command:

$ git status

On branch master

Changes to be committed:

  (use "git reset HEAD ..." to unstage)
new file: EXAMPLE
This information tells us that there are changes to be committed and that the file has been staged.

### Committing a File
After staging one or multiple files, you should commit the changes and record what you did within the commit message:

$ git commit -m “made change x,y,z”
*This step has committed changes for the file or files (you can have one commit message for multiple files, if applicable) to the HEAD.

### Committing All Changes
$ git commit -a
*This command commits a snapshot of all modifications to tracked files in the working directory.

### Pushing Changes
Next, you would push changes to a remote repository. We will discuss remote repositories in more depth in the next section. For now, we will look at a general overview of pushing changes to remotes.

### Stashing Changes
When you are not ready to commit changes but do not want to lose them either, git stash is a great option. This command temporarily removes changes and hides them, giving you a clean working directory. When you are ready to continue working on the changes, simply use the git stash apply command to retrieve the hidden changes.
