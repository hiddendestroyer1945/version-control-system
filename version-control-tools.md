# Version Control System Tools
*   **Description**: To explain the types of version controls, types of version control tools and installation of distributed version control tool git in local system.

*   **Types of Version Controls**: Three types of version controls are there. They are Local Version Control, Centralized Version Control, and Distributed Version Control.
    *   **Local Version Control**: Local version control is a type of version control where the version control system is installed on the local machine. It is the simplest type of version control and is used for small projects.
    *   **Centralized Version Control**: Centralized version control is a type of version control where the version control system is installed on a central server. It is the most common type of version control and is used for medium to large projects.
    *   **Distributed Version Control**: Distributed version control is a type of version control where the version control system is installed on the local machine and a central server. It is the most advanced type of version control and is used for large projects.

*   **Version Control Tools**: Some of the tools used for version control are Git, SVN, and Mercurial.
    *   **Git**: Git is a distributed version control system that is used for version control. It is the most popular version control system and is used by many open source projects and many large scale projects.
    *   **SVN**: SVN is a centralized version control system that is used for version control. It is the most common version control system and is used by many small scale projects. But now it is not used much.
    *   **Mercurial**: Mercurial is a distributed version control system that is used for version control. It is the most advanced version control system and is used by many proprietary enterprise projects.

*   **Installation and Configuration of Git**: Distributed version control system tool git can be installed and configured on the local machine. Git Installation and configuration have five steps. first is git installation then user name configuration then email configuration then pulling by rebase configuration then check the git configuration.

*   **Installation**: 

```bash
sudo apt update && sudo apt upgrade -y
sudo apt install git
```

*   **User Name Configuration**:

```bash
sudo git config --global user.name "Your User Name"
```

*   **Email Configuration**:

```bash
sudo git config --global user.email "Yor Email Id"
```

*   **Pulling by Rebase Configuration**:

```bash
sudo git config --global pull.rebase false
```

*   **Check the Git Configuration**:

```bash
sudo git config --list
```

