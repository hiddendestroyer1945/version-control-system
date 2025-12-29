# Version Control History
*   **Description**: To explain about the version control git history, version control git primary branches, version control git Head, make the version control git history, check the version control git history, check the version control git status and more related to git history.
*   **Version Control Git History**: A version control history is a stories about all files and directories in repository of a project. It is used to track changes to the files and directories, and to revert to previous versions if needed.
*   **Types of Git History**: Two types of history are used for git distributed version control system. They are local history and remote history. The project is completed by having these two history work in conjunction with each other.
    *   **Local Git History**: A local history is a history that is stored on the local repository. It is used to track changes to the files and directories of local repository.
    *   **Remote Git History**: A remote history is a history that is stored on the remote server. It is used to track changes to the files and directories of remote repository.
*   **Version Control Git Primary Branches**: The primary branch, called master, is the branch that is created when the create the initial commit on the local Git repository.But primary branch, called main, is the branch that is created when the create remote repository  and add the file.
*   **Version Control Git Head**: The head is a pointer to the latest commit in the current branch. It is used to track the latest commit in the current branch.When create the initial commit of git local repository then Head is created.
*   **Git History**: The git history creating for tracking the changes to the files and directories, and to revert to previous versions if needed. Project have a two type git history local and remote.
*   **Local Git History**: The git local history creating in local git repository for tracking the changes to the files and directories, and to revert to previous versions if needed.

**Local Git History Creation**: 

```bash
git add "created or modified file name"
git commit -m "commit message"
```
**Local Git History Checking**: 

```bash
git log
```
**Whole Local Git History Checking**: 

```bash
git log -all
```
**Local Git History Checking With Branch Graph**: 

```bash
git log --decorate --graph
```
**Local Git Repository Status Checking**: 

```bash
git status
```
**Local Git Specific History With Modification Checking**: 

```bash
git show "specific commit Id"
```
**Local Git Specifc File Based Histories Checking**: 

```bash
git log -p "specific file name"
```
**Local Git Last Change Checking**: 

```bash
git diff
```
**Local Git Specific Commit Modifications Checking**: 

```bash
git diff "specific commit Id"
```
**Local Git Untracked Modifications Wiping**: 

```bash
git stash
```
**Local Git History Deleting Till Specific HEAD Point**: 

```bash
git reset --hard "specific HEAD point(eg:HEAD~1 or HEAD~2)"
```
*   **Remote Git History**: The git remote history creating in remote git repository for tracking the changes to the files and directories, and to revert to previous versions if needed. But when you make any changes to files in Git remote repository or create any new files in remote repository, you will automatically navigate to the commit page to create its history. But click the commit button navigating to the commit page for listing and checking the commits.