[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15297083&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
  * I Select and install a text editor or IDE suitable for my programming languages and workflow. I Download and Install Visual Studio Code. https://code.visualstudio.com/Download.
  * Select the appropriate installer for my operating system (Windows) and download it.
  * Run the Installer:
    - I Open the downloaded installer file and follow the on-screen instructions.
    - I Accept the license agreement and select the installation location.
    - I Choose a additional tasks such as adding VS Code to my system PATH, creating a desktop icon, etc.
    - I Click "Install" to begin the installation process.
    - I Once the installation is complete, I click "Finish" to launch Visual Studio Code.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com:
 * Install Git
   I Visit the Git Download Page:
   I went to the Git download page.
   Download the Installer:
   I Select the appropriate installer my operating system (Windows) and download it.
 * I Run the Installer (Windows):

  - I Open the downloaded installer file.
  - I Followed the installation wizard:
    I Choose the installation location(Desktop),
    Select the components to install (default options are usually fine),
    Adjust the PATH environment (use Git from the command line and also from 3rd-party software),
    Choose the HTTPS transport backend (default option),
    Configure the line ending conversions (recommended option), and
    Complete the installation process.

 * Verify Installation:
  
  - I Open a terminal or command prompt.
  - I Type the following command to check the Git version:
     pc@DESKTOP-FG6MT4E MINGW64 ~ (master)
     $ git --version
     git version 2.45.2.windows.1

 * Configure Git on My Local Machine
   Set Up My Name and Email:

  I Open Git Bash terminal.
  I Configure My Git user name and email:
  pc@DESKTOP-FG6MT4E MINGW64 ~ (master)
    $ git --version
    git config --global user.name "Ejima Emmanuel Ojodomo"
    git config --global user.email "emmanuelejima12@gmail.com"

 * Verify Configuration:
   
   pc@DESKTOP-FG6MT4E MINGW64 ~ (master)
   $ git config --list
   diff.astextplain.textconv=astextplain
   filter.lfs.clean=git-lfs clean -- %f
   filter.lfs.smudge=git-lfs smudge -- %f
   filter.lfs.process=git-lfs filter-process
   filter.lfs.required=true
   http.sslbackend=openssl
   http.sslcainfo=C:/Program Files/Git/mingw64/etc/ssl/certs/ca-bundle.crt
   core.autocrlf=true
   core.fscache=true
   core.symlinks=false
   pull.rebase=false
   credential.helper=manager
   credential.https://dev.azure.com.usehttppath=true
   init.defaultbranch=master
   user.name= Ejima Emmanuel Ojodomo
   user.email=emmanuelejima12@gmail.com
   core.repositoryformatversion=0
   core.filemode=false
   core.bare=false
   core.logallrefupdates=true
   core.symlinks=false
   core.ignorecase=true

 * Create a New Repository on GitHub
   
   Log in to My GitHub account (github.com/EmmanuelEjima)
   
 * Create a New Repository:

  - I Click on the "+" icon in the upper-right corner and select "New repository".
  - I Fill in the repository details:
  Repository name (Assignment),
  Description (optional),
  Public or private repository,
  Initialize with a README (optional), and
  I Click "Create repository".

 * Initialize a Git Repository Locally and Make My Commit
   I Open GIT BASH Terminal 
 - pc@DESKTOP-FG6MT4E MINGW64 ~/Assignment (master)
   $ mkdir Assignment
 - pc@DESKTOP-FG6MT4E MINGW64 ~/Assignment (master)
   $ cd Assignment

 * Initialize a Git Repository:

  pc@DESKTOP-FG6MT4E MINGW64 ~/Assignment (master)
  $ git init
  Reinitialized existing Git repository in C:/Users/pc/Assignment/.git/

 * Add Files to the Repository:

 Create a README file:

  pc@DESKTOP-FG6MT4E MINGW64 ~/Assignment (master)
  $ echo "#Assignment" > README.md

 * Add the file to the staging area:
 
  pc@DESKTOP-FG6MT4E MINGW64 ~/Assignment (master)
  $ git add README.md
   warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

 * Commit the Files:

  pc@DESKTOP-FG6MT4E MINGW64 ~/Assignment (master)
  $ git commit -m "Initial commit"
  [master (root-commit) 4dbad80] Initial commit
  1 file changed, 1 insertion(+)
  create mode 100644 README.md

 * Connect to the Remote Repository on GitHub:

  @DESKTOP-FG6MT4E MINGW64 ~/Assignment (master)
  $ git remote add origin https://github.com/EmmanuelEjima/Assignment.git

 * Push the Local Repository to GitHub:

  pc@DESKTOP-FG6MT4E MINGW64 ~/Assignment (master)
  $ git push -u origin master
  Enumerating objects: 3, done.
  Counting objects: 100% (3/3), done.
  Writing objects: 100% (3/3), 235 bytes | 117.00 KiB/s, done.
  Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
  remote:
  remote: Create a pull request for 'master' on GitHub by visiting:
  remote:      https://github.com/EmmanuelEjima/Assignment/pull/new/master
  remote:
  To https://github.com/EmmanuelEjima/Assignment.git
  [new branch]      master -> master
  branch 'master' set up to track 'origin/master'.



4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  Visit the Python Download Page:

  Go to the Python download page.
 * Download the Installer:

 - I Click on the "Download Python" button for the latest version installer for My operating system (Windows).
 
 * Run the Installer (Windows):

 - I Open the downloaded installer file and
   Click on "Install Now" and I follow the installation instructions.


 * Verify Installation:

 - Open Git Bash terminal To check the Python version:

   pc@DESKTOP-FG6MT4E MINGW64(master)
   $ Python --version
   Python 3.12.3


5. Install Package Managers:
   If applicable, install package managers like pip (Python). 

 *  Verify pip Installation:

 - I Open Git Bash terminal To check the pip Python version:
    pc@DESKTOP-FG6MT4E MINGW64 ~ (master)
   $ python -m pip --version
   pip 24.0 from C:\Users\pc\AppData\Local\Programs\Python\Python312\Lib\site-packages\pip (python 3.12)


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
 * I installed MySQL database

 * Verify MySQL Command:
 - I Open a new command prompt:
  Run the MySQL Command:
  
  C:\Users\pc>mysql -u root -p
  Enter password: **********
  Welcome to the MySQL monitor.  Commands end with ; or \g.
  Your MySQL connection id is 9
   Server version: 8.0.37 MySQL Community Server - GPL
   Copyright (c) 2000, 2024, Oracle and/or its affiliates.

    Oracle is a registered trademark of Oracle Corporation and/or its
     affiliates. Other names may be trademarks of their respective
     owners.
    Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.
   mysql>
7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
 
 * Open Visual Studio Code

 - I Open the Extensions View and Click on the Extensions icon in the Activity Bar on the side of the window.
 - Search and Install Extensions
   
   Flutter:
  
  Search for Flutter Extension:
  In the Extensions view, I type Flutter in the search box.
  Install Flutter Extension:
  Click the Install button for the "Flutter" extension by Dart Code.
  Python:

  Search for Python Extension:
  In the Extensions view, I type Python in the search box.
  Install Python Extension:
  Click the Install button for the "Python" extension by Microsoft.
  
  Dart:
 Search for Dart Extension:
  In the Extensions view, type Dart in the search box.
  Install Dart Extension:
 Click the Install button for the "Dart" extension by Dart Code.
 
 Path Intellisense:
 Search for Path Intellisense Extension:
 In the Extensions view, type Path Intellisense in the search box.
 Install Path Intellisense Extension:
 Click the Install button for the "Path Intellisense" extension by Christian Kohler.

 * Verify Installation:
  After installing the extensions, I verify their installation:
  I Go to the Extensions view again and  I see the installed extensions listed under "Enabled".


9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

 *  Install Operating System
  Operating System: Windows 11
  Download Link: Windows 11 Download
  Follow the installation wizard to install Windows 11 on your machine.
 * Install Visual Studio Code
  Download Link: Visual Studio Code
  Follow the installation instructions to install VS Code on your machine.
* Install Python
  Download Link: Python Download
 Run the installer:
 Check "Add Python to PATH".
  Click "Install Now".
 - Verify installation:
  Git Bash

  python --version
  pip --version

* Set Up MySQL
  Download Link: MySQL Installer
  Follow the installation instructions.
  Add MySQL to the system PATH:
  Navigate to C:\Program Files\MySQL\MySQL Server <version>\bin.
  Add this path to the system environment variables.
 
 
 * Install and Configure Git
   Download Link: Git Download
   Follow the installation instructions.
 - Configure Git:
 
   git config --global user.name "Your Name"
   git config --global user.email "youremail@example.com"
 
 * Create a GitHub account: GitHub

 * Set Up VS Code Extensions
 - Open VS Code.

 - Open Extensions view (Ctrl+Shift+X or Cmd+Shift+X).

 - Install the following extensions:

   Flutter:
   Search for "Flutter" and click "Install".

   Python:
   Search for "Python" and click "Install".

   Dart:
   Search for "Dart" and click "Install".

   GitLens:
   Search for "GitLens" and click "Install".

   Path Intellisense:
   Search for "Path Intellisense" and click "Install".

 *  Create and Configure a Virtual Environment for Python

 * Navigate to your project directory.
 
   Create and activate a virtual environment:
   Git Bash
   python -m venv env
  .\env\Scripts\activate  # Windows
  source env/bin/activate  # macOS/Linux
  Install necessary packages:

  pip install <package_name>
 
* Document Setup
Create a README.md file in your project directory.
Add setup instructions and any relevant information.
Sample README.md Content
markdown
Copy code
# My Project



 ## Setup Instructions


### Prerequisites
- Windows 11
- Visual Studio Code
- Python 3.x
- MySQL
- Git

### Installation Steps

. **Install Python**:
  
   Git Bash
   python --version
   pip --version
 
 * Set Up Virtual Environment:
  Git Bash
 python -m venv env
 .\env\Scripts\activate  # Windows
 source env/bin/activate  # macOS/Linux
 pip install -r requirements.txt
 
 * Install MySQL:

 Follow the MySQL Installer instructions.

 * Configure Git
 Git Bash
 git config --global user.name "Your Name"
 git config --global user.email "youremail@example.com"
 
 
 * Install VS Code Extensions:

  Flutter, Python, Dart, GitLens, Path Intellisense
  Usage
  Run the project:
  Git Bash
  python main.py


* Troubleshooting

- Ensure all paths are correctly set in the system environment variables.
- Check the installation and configuration of all tools.
- Use AI for Troubleshooting when faced setup challenges.



