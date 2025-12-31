# Version Control Repository
*   **Description**: To explain about the version control repository, types of version control repositories, how to use them, git local repository setup, git server repository setup and distributed version control git servers.

*   **Version Control Repository**: A version control repository is a database that stores all the files and directories of a project, along with their history. It is used to track changes to the files and directories, and to revert to previous versions if needed.

*   **Types of Git Repositories**: Two types of repositories are used for git distributed version control system. They are local repository and remote repository. The project is completed by having these two repositories work in conjunction with each other.
    *   **Local Git Repository**: A local repository is a repository that is stored on the local machine. It is used to store the files and directories of a project, and to track changes to the files and directories.
    *   **Remote Git Repository**: A remote repository is a repository that is stored in a remote server on internet. It is used to store the files and directories of a project, and to track changes to the files and directories.
    
*   **How to Use Git Repositories**: To use git repositories, you need to have a git client installed on your local machine. You can use git client to clone a repository, push changes to a remote repository, pull changes from a remoterepository, and more. 

*   **Git Local Repository Setup**: Setup the git local repository for working in git project. This have four steps. first create a git repository in local machine, second initialize the git repository, third add the files to the git repository, and fourth initial commit the files to the git repository.

**Create the git local repository**    
```bash
mkdir "Your Project Name"
cd "Your Project Name"
``` 

**Initialize the git repository**:
```bash
git init
``` 

**Add the files to the git repository**:
```bash
git add "Your File Name"
``` 

**Initial commit the files to the git repository**:
```bash
git commit -m "Initial commit message"
``` 

**check the log of the git repository initial commit**:
```bash
git log
``` 

*   **Git Server Repository Setup**: Setup the git server repository for working in git project. This have four steps. first create a git repository in server, second configure the private of public in that repository, third add the files to the git server repository, and fourth click the create button in git server repository.
    
*   **Distributed Version Control Git Servers**: any git servers is available in internet. The famous git servers are GitHub, GitLab, and Bitbucket.
    *   **Github**: It mostly used for open source projects. https://github.com is this server link.
    *   **Gitlab**: It mostly used for private projects. https://gitlab.com is this server link.
    *   **Bitbucket**: It is used for private projects. It's security is better than github and gitlab. https://bitbucket.org is this server link.