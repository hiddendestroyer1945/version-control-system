# Version Control Branches
*   **Description**: To explain about the version control branches, specifications of branching, working of branches, type of branches, git branch making, git branches deleting and more related to branching.

*   **Version Control Branches**: Every branches are acting like a different workspace. Every category of activity have a different branch in project.The activities of one branch does not affect other branches at all.
*   **Version Control Branches Specifications**: Each category of activity has different branches in the project, so activities can be performed without affecting other branches. Every branches can merging for needed time of put the whole activity together.After merging can doing the activities in each specific branches. The work of each branch prior to the merge is combined in the merge, but the work done in each branch after the merge remains separate.
*   **Version Control Branches Types**: There are two types of branches have in a every git projects. One is the main branches and other is feature branches.
    *   **Types of Main Branches**: Main branches are the primary branches of the project. There are two types of main branches. One is the main branch in remote repository, other is the master branch in local repository.
    *   **Master Branch**: Master branch is the main branch type of the local repository. It is the default branch of the local repository. It is the branch which is used for the main code of the project.
    *   **Main Branch**: Main branch is the main branch type of the remote repository. It is the default branch of the remote repository. It is the branch which is used for the main code of the project.
    *   **Types of Feature Branches**: Feature branches are the branches of the project. There are three types of feature branches. One is the development branches and second is hotfix branches and other is release branches.
    *   **Development Branch**: Development branch is the feature branch type of the local repository. It is the branch which is used for the development code of the project. Many development branches can be created in the local repository. Python development branch, deveop development branch, project development branch etc.
    *   **Hotfix Branch**: Hotfix branch is the feature branch type of the local repository. It is the branch which is used for the hotfixing, bugfixing, security fixing and testing code of the project. Only one hotfix branch can be created in the local repository.
    *   **Release Branch**: Release branch is the feature branch type of the local repository. It is the branch which is used for the release code of the project and marketing code of the project. Only one release branch can be created in the local repository. 
*   **How to Use Version Control Branches**: To use version control branches, firstly make the local repository and create the local repository master branch using with initial commiting. Then master branch create the main feature branch for managing the development. Then main development feature branch create the other specific development feature branches. Then main development feature branch create the hotfix feature branch. Then main development feature branch create the release feature branch. Then local repository master branch create the remote repository and create the remote repository main branch using with initial commiting.

-   Then local repository master branch adding the remote repository in local repository. Then local repository development management branch create the project guidlines document with it's history. Then local repository development management branch pushing in remote repository. Then remote repository main branch configure the feature branches collaborators. 

-   Then local repository development management branch create the project's prd file, tdd file, sow register file for project planning. Then local repository development management branch pushing in remote repository. Then remote repository development management branch create and give the work requests via discussion based on sow register to the development feature branches collaborators. Then remote repository development feature branches's collaborators clone the their development feature branches clone to their local systems and start working on their development feature branches.

-   Then remote repository development feature branches's collaborators push their development feature branches in remote repository after every work request's work are completed. And infofrmed that via discussion comment to the remote repository development management branch.

-   Then remote repository development management branch create and give the work requests via discussion based on sow register to the hotfix feature branches collaborators. Then remote repository hotfix feature branch's collaborators clone their hotfix feature branches clone to their local systems. Then remote repository hotfix feature branch's collaborators pulling the remote repository development feature branches in local repository and start working on their hotfix feature branches.

-   Then remote repository hotfix feature branches's collaborators push their hotfix feature branches in remote repository after every work request's work are completed. And infofrmed that via discussion comment to the remote repository development management branch. Then if remote repository hotfix feature branches's collaborators finding the errors or bugs in developed codes that informed via issues to the remote repository development management branch. Then remote repository development management branch create and give the new work requests via discussion based on updated sow register and issues to the development feature branches collaborators.

-   Then remote repository development feature branches's collaborators push their development feature branches in remote repository after every issues based work request's work are completed. And infofrmed that via discussion comment to the remote repository development management branch.

-   Then remote repository development management branch create and give the work requests via discussion based on sow register to the release feature branch collaborators. Then remote repository release feature branch's collaborators clone their release feature branch clone to their local systems and start working on their release feature branches.

-   Then remote repository release feature branch's collaborators push their release feature branches in remote repository after every work request's work are completed. And informed that via discussion comment to the remote repository development management branch.

-   Then if project's work are completed merging the development feature branches and release feature branch are merged into the local repository master branch. Then remote repository main branch rebase pulling in local repository master branch. Then local repository master branch merging in local repository main branch. Then local repository main branch pushing in remote repository main branch.

*   **Local Repository Branches**: Explaining the local repository branches related commands.

**Create the Local Repository Feature Branches**:

```bash
git branch "feature-branch-name"
``` 

**List the Local Repository Branches**:

```bash
git branch
``` 

**Checkout the One Branch to Other Branch**:

```bash
git checkout "branch name"
```

**Delete the Local Repository Feature Branches**:

```bash
git branch -d "feature-branch-name"
```

*   **Remote Repository Branches**: The remote repository branches are listing in drop down button of remote repository. Can select the required branches from that drop-down button and access data from that specific branch. Can create the required branches in the remote repository by entering the required names in the search bar in that drop-down button and using the Create Branch button in that drop-down button