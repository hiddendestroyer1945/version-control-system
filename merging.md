# Version Control Merging

*   **Description**: To explain about the version control merging, specifications of merging, type of merging, steps of merging and execution of merging.

*   **Version Control Merging**: Merging is the process of combining the changes and it's history from one branch into another branch. It is used to combine the changes from the feature branch into the main branch.

*   **Version Control Merging Specifications**: When doing merging merged the other branches into currently accessed specific branch. When before the merging must be completing the history making in source branch and target branches.When merging preserved unchanged the history of source branch and target branches. When merging must ensure the branches are bugfree and errorfree. When merging fast forward merging using for excluding the merging history. Recursive merging is used to build merge history when merging. When merging target branches is not going away.

*   **Version Control Merging Types**: There are six types of merging. They are fast forward merging, recursive merging, octopus merging, subtree merging, squash merging and ours merging.

    *   **Fast Forward Merging**: Fast forward merging is used for excluding the merging history. 

    *   **Recursive Merging**: Recursive merging is used to build merge history when merging. 

    *   **Octopus Merging**: Octopus merging is used to merge multiple branches into a single branch. 

    *   **Subtree Merging**: Subtree merging is used to merge a another repository branches into a single branch. 

    *   **Squash Merging**: Squash merging is used to merge multiple history of target branch into single history of source branch. 

    *   **Ours Merging**: Ours merging is used to merge history only from target branch into source branch.

*   **Version Control Merging Steps**: The steps of merging are as follows.
    *   **Step 1**: Create a new branch from the master branch.
    *   **Step 2**: Make changes in the new branch.
    *   **Step 3**: Commit the changes in the new branch.
    *   **Step 4**: Merge the new branch into the master branch.
    *   **Step 5**: Push the changes to the remote repository.

*   **Local Repository Merging**: Explaining the merging the local repository branches related commands.

**Fast Forward Merging**: 
```bash
git checkout "source-branch"
git merge "target-branch"
``` 
**Recursive Merging**: 
```bash
git checkout "source-branch"
git merge --no-ff"target-branch"
``` 
**Octopus Merging**: 
```bash
git checkout "source-branch"
git merge -s octopus "1st target-branch" "2nd target-branch"
``` 
**Subtree Merging**: 
```bash
git checkout "source-branch"
git remote add "target repository name" "target repository path/"
git subtree add --prefix="target repository name" "target repository name in local repository" "target-branch in target repository"
```
 **Subtree With Squash Merging**: 
```bash
git checkout "source-branch"
git remote add "target repository name" "target repository path/"
git subtree add --prefix="target repository name" "target repository name in local repository" "target-branch in target repository" --squash
```  
**Squash Merging**: 
```bash
git checkout "source-branch"
git merge --squash "target-branch"
``` 
**Ours Merging**: 
```bash
git checkout "source-branch"
git merge -s ours "target-branch"
``` 
**Checking Merge Result Using Log**: 
```bash
git checkout "source-branch"
git log
``` 

*   **Remote Repository Merging**: After get the new branch in remote repository create and submit the pull request, then merging after select the source branch and target branch.