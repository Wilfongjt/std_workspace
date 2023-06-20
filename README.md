# std_workspace
Maintain consistent work environment for multiple clients.
Title and Description: Start with a clear and descriptive title that conveys the purpose of your project. 
Follow it with a brief summary that explains what your project does and why it's useful or interesting.

* __Add Workspace__
* __Add GitHub Project__
* __Save GitHub Project__
* __Archive Workspace__
* __Restore Archived Workspace__

### Table of Contents: 
TBD - If your README is lengthy, include a table of contents to help users quickly navigate to specific sections.

### Definitions
* __\<GH_ACCOUNT>__ is a specific github account.
* __Remote Source__ is the std_workspace repository on GitHub.
* __Local Source__ is the std_workspace repository on your machine.
* __Developement__ is the name of the folder where I put all my code.
* __Organization__ is a person or a client. 
* __\<ORGANIZATION>__ is a specific organization (no spaces).
* __Workspace__ is a group of projects.
* __\<WORKSPACE>__ is a specific workspace (no spaces).
* __Project__ is a repository.
* __\<PROJECT>__ is a specific repository (no spaces).
* __Branch__ is the name of current repository branch.

# Installation: 
Two part installation: 
1. install the repository and then 
1. install the runtime application.

## Repository Install
### Dependencies
#### Python 3
1. Install Python 3

### The Repository Installation

__Tasks__

* Open a command window
* Navigate to your home folder, eg cd ~/
* Create one folder to store all development
* Create an organization
* Create a workspace
* Clone std_workspace
 
__Commands__
   
   ```commandline
    cd ~
    
    mkdir Development/

    cd Development/
    mkdir <ORGANIZATION>/
    
    cd <ORGANIZATION>/
    mkdir <WORKSPACE>/
    
    cd <WORKSPACE>/
    git clone  https://github.com/<<GH_ACCOUNT>>/<PROJECT>.git
    
    cd <PROJECT>/
   ```

## Application Runtime Install
Once you have installed the repository,
You must install a seperate application.

1. Open a command window

1. Run the Tool Install script
   ```commandline
   cd ~/<ORGANIZATION>/<WORKSPACE>/py_workspace/
   python3 install.py
   ```

# Usage: 
Once the runtime application is installed,
the application can create an organization, a workspace, and a project.

Explain how users can use your project. 
Provide examples, code snippets, or instructions to demonstrate how to utilize the various features and functionalities. 
Include any necessary configuration or setup steps.

### Add Workspace
Add a Workspace to a specified Organization
   ```commandline
   cd ~/Development/_tools
   ./git.ws.sh  
   ```
### Add Project (GitHub Repo)
Add Project to a specified Organiztion and  Workspace.
   ```
   cd ~/Development/<ORGANIZATION>/<WORKSPACE>/<PROJECT>/scripts
   ./git.branch.sh
   ```
### Save Project (GitHub Repo)
Rebase the current branch.
   ```
   cd ~/Development/<ORGANIZATION>/<WORKSPACE>/<PROJECT>/scripts
   ./git.rebase.sh
   ```
### Archive TBD
Sometimes GitHib isn't enough

### Restore Archive TBD
TBD

# Documentation: 
TBD - If your project has extensive documentation, provide links or instructions on how to access it. 
This could include links to a separate documentation website, wiki, or specific sections within your repository.

### Contributing: 
TBD - Encourage others to contribute to your project by providing clear guidelines on how to get started, submit bug reports, propose new features, or contribute code. 
Include any code formatting conventions, testing guidelines, or contribution workflows that you expect contributors to follow.

### License: 
TBD - Specify the license under which your project is released. 
It's essential to clarify the permissions and restrictions associated with your codebase.

### Changelog: 
TBD - Maintain a changelog that summarizes the significant changes made to your project in each version release. 
This helps users understand what's new and assists in tracking the project's progress.

### Credits and Acknowledgments: 
TBD - Give credit to any individuals, libraries, or resources that have influenced or assisted your project. 
Include links to their repositories or relevant websites.

### Contact Information: 
TBD - Provide a way for users to get in touch with you, whether it's through email, social media, or a dedicated issue tracker.

### Badges: 
TBD - Optional but helpful, include badges in your README to highlight project status, build passing/failing, code coverage, and other relevant metrics. 
Badges can quickly convey project information at a glance.