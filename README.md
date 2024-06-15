[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15271738&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.






                                   ANSWERS TO ASSIGNMENT :1


HOW TO INSTALL WINDOWS 11

Steps to Download and Install Windows 11

1.	Check Compatibility:

o	 I Used the PC Health Check tool from Microsoft to verify if my current PC meets the minimum requirements for Windows 11.

2.	Backup Your Data:

o	Before upgrading, I   backed up all important files. 

3.	Get Windows 11:

o	I   downloaded  the Windows 11 installation media from the Microsoft website  to perform a clean installation.

4.	Create Installation Media (Optional):

o	I followed the instructions to create installation media on a USB drive.

5.	Install Windows 11:

o	I inserted  installation media it into the PC and run the setup.exe file.

6.	Complete Setup:

o	I followed the prompts to set up Windows 11, including signing in with my Microsoft account and configuring my preferences.

7.	Update Drivers and Apps:

o	After installation, I checked for updated drivers for my hardware (especially graphics and network drivers) and updated my apps from the Microsoft Store or respective websites.

Additional Tips:

•	Check for Updates: After installation ,  I ensured Windows 11 is up to date by going to Settings > Update & Security > Windows Update.



Downloading Visual Studio Code

1.	Visit the Official Website:

o	I went to the Visual Studio Code website.

2.	Download the Installer:

o	On the main page I clicked prominent download button on it to download the installer appropriate for my operating system (Windows).
Installing Visual Studio Code

1.	Run the Installer:

o	When the download was  complete, I located the installer file (typically named VSCodeSetup.exe) and double-click it to start the installation process.

2.	Accept License Agreement:

o	I followed the prompts in the setup wizard. I accepted the license agreement and choose the destination folder where I want to install VS Code.
3.	Select Additional Tasks:

o	During installation I selected additional tasks such as adding VS Code to the PATH variable and creating desktop shortcuts. 



SETTING UP VERSION CONTROL SYSTEM

1.	Download Git:

o	I visited the Git website and download the installer for Windows.

2.	Run the Installer:

o	I ran the installer (typically named Git-x.x.x-64-bit.exe, where x.x.x represents the version number).

3.	Setup Wizard:

o	Follow the prompts in the setup wizard:

	I chose the components to install.

	I selected the destination folder (typically C:\Program Files\Git).

	I chose the default editor for Git.

	I adjusted my PATH environment : I selected  "Use Git and optional Unix tools from the Command Prompt" to use Git Bash.

	I chose HTTPS transport backend (leave default "Use the OpenSSL library" selected).

	I configured line ending conversions (leave default "Checkout Windows-style, commit Unix-style line endings" selected).

	I chose terminal emulator (leave default "Use MinTTY" selected).

	I chose extras (options to enable file system caching, credential manager, etc.).

	Select to start the Git Bash.

I went github.com and created w github account

Initializing a Git Repository

1.	Open Terminal or Command Prompt:

o	I navigated to the directory where I wanted to initialize my Git repository. I used the cd command to change directories.

2.	Initialize Git:

o	I ran the following command to initialize a new Git repository:

git init

o	This command creates a new .git directory in the current folder, which contains all the necessary files for Git to manage the repository.

Making Commits

1.	Add Files to Staging Area:

o	Before committing changes, I needed to add files to the staging area. This tells Git which changes I want to include in the next commit.

o	To add a specific file to the staging area:
git add filename

o	To add all files (recommended when you've made changes to multiple files):
git add .

2.	Commit Changes:

o	Once files are added to the staging area, I commited them with a descriptive message. The commit message should briefly describe the changes made in the commit.

o	To commit with a message:

git commit -m "Your commit message here"

o	Replace "Your commit message here" with a meaningful description of the changes.

3.	View Commit History (Optional):

o	I viewed the commit history to see a list of commits made to the repository:

git log

o	This command displays a list of commits, showing the commit hash, author, date, and commit message.
Example Workflow

Let's walk through an example workflow to clarify:

1.	Initialize a Git repository:

cd /path/to/your/project

git init

2.	Create or modify files in your project directory.

3.	Add files to the staging area:

git add .

4.	Commit changes with a descriptive message:

git commit -m "Initial commit"

5.	View commit history to verify your commit:

git log

Additional Git Commands

•	Status: I Checked the status of my working directory and staging area.
git status

•	Diff: Show changes between commits, the working directory, and the staging area.
git diff

•	Branches: List, create, or delete branches
git branch

git branch new-branch-name

git branch -d branch-to-delete

•	Remote Repositories: Manage remote repositories (e.g., GitHub, GitLab).

git remote add origin <remote-repository-url>

git push -u origin master



INSTALLING PYTHON

1.	Download Python Installer:

o	I visited the official Python website and download the latest version of Python suitable for my operating system (Windows).

2.	Run the Installer:

o	Once the download was complete, I ran the installer. I checked the box that says "Add Python to PATH" during installation. This will allows  running Python and its tools from the command line.

3.	Verify Installation:

o	After installation, I opened a terminal or command prompt and type:

python --version
o	This command  displayed the installed Python version. 

Installing Python Compilers (Interpreters)

Python itself doesn't need a separate compiler as it is an interpreted language. However, you might need to install additional tools or compilers depending on your development needs, such as for compiling native extensions or optimizing Python code. 



INSTALLING PACKAGE MANAGERS OF PYTHON

1.	Download get-pip.py:

o	Download the get-pip.py script by visiting https://bootstrap.pypa.io/get-pip.py.

2.	Run the Script:

o	Open a command prompt and navigate to the directory where you downloaded get-pip.py.

o	Run the script using Python:
python get-pip.py

o	This will download and install pip and its dependencies.

3.	Verify Installation:

o	After installation, verify pip by running:

pip –version
Using pip
Once pip is installed, I use it to install Python packages from the Python Package Index (PyPI). Here are some basic commands:

•	Install a Package:
pip install package-name

•	Upgrade a Package:
pip install --upgrade package-name

•	Uninstall a Package:
pip uninstall package-name

•	List Installed Packages:
pip list



DOWNLOADING, INSTALLING AND CONFIGURATION OF MYSQL.

Downloading MySQL

1.	Visit the MySQL Website:

o	Go to the MySQL Community Downloads page.

2.	Select MySQL Community Server:

o	I chose the MySQL Community Server version suitable for my operating system. I selected the appropriate installer package (usually a .msi for Windows).

3.	Download the Installer:

o	I clicked on the download link and followed the prompts to download the installer.

Installing MySQL

For Windows:

1.	I run the Installer:

o	I Double-clicked the downloaded .msi file to launch the MySQL installer.

2.	Setup Type:

o	Choose the setup type (typically "Developer Default" for a quick installation with commonly used features). Click Next.

3.	Installation:

o	Follow the installer prompts to complete the installation. You may be prompted to set a root password during installation. Make sure to remember this password, as it is crucial for accessing MySQL.

4.	Start MySQL Server:

o	MySQL should start automatically after installation. 

Configuring MySQL

1.	Access MySQL Shell:
o	Open a terminal or command prompt and log in to MySQL as the root user:
mysql -u root -p

o	Enter the root password when prompted.

2.	Create MySQL Users and Databases:

o	I created additional MySQL users and databases as needed:

CREATE DATABASE dbname;

CREATE USER 'username'@'localhost' IDENTIFIED BY 'password';

GRANT ALL PRIVILEGES ON dbname.* TO 'username'@'localhost';

FLUSH PRIVILEGES;

3.	Configure MySQL Options :

o	MySQL configuration file (my.cnf or my.ini) is located in different places . I adjusted settings like max_connections, innodb_buffer_pool_size, etc., based on your system's requirements.

4.	Restart MySQL Server:

o	After making any changes to the configuration file,  I restarted the MySQL service:
sudo systemctl restart mysql  # For systemd-based systems
Using MySQL

Once MySQL is installed and configured, I connected to it using various tools such as MySQL Workbench, command-line interface (CLI), or programming language APIs (e.g., Python's mysql-connector-python).

•	CLI: Use mysql command-line tool to interact with MySQL:
mysql -u username -p dbname




EXTENSIONS AND PLUGINS IN VISUAL STUDIO CODE

Visual Studio Code (VS Code) offers a rich ecosystem of extensions that can greatly enhance  coding experience. Here are some categories of extensions I explored to improve functionality in VS Code:

1. Language Support (Syntax Highlighting, IntelliSense)

•	Python: Provides syntax highlighting, code completion, and linting for Python.

•	JavaScript (ESLint, TypeScript): Offers syntax highlighting, IntelliSense, and integrates with ESLint for linting JavaScript and TypeScript code.

•	Java: Provides language support, debugging capabilities, and IntelliSense for Java development.

2. Linting and Code Quality

•	ESLint: Linter for JavaScript and TypeScript that helps enforce coding standards.

•	Pylint: Linter for Python that checks for errors, code style, and helps improve code quality.

•	PHP Intelephense: Provides code quality tools, support for frameworks, and code analysis.

3. Code Formatting

•	Prettier - Code formatter: Automatically formats code to ensure consistency across your project.

•	Python - Formatting: Formats Python code according to specified standards (e.g., PEP 8).

4. Version Control Integration

•	GitLens: Enhances Git integration with features like blame annotations, repository/file history, and more.

•	GitHub Pull Requests: Manages and reviews GitHub pull requests directly within VS Code.

5. Debugging

•	Debugger for Chrome: Debug JavaScript applications running in the Chrome browser.

•	Python - Debugger (extension): Provides debugging support for Python applications.

6. Themes and UI Enhancements

•	Material Theme: Offers Material Design-inspired themes for VS Code.

•	Icons: Provides sets of icons to make it easier to distinguish file types and components.

7. Productivity

•	Live Share: Collaborative editing and debugging in real-time with teammates.

•	Todo Tree: Highlights TODO comments and tracks them in a tree view.

Installing Extensions in VS Code

1.	Access Extensions Marketplace:

o	I opened VS Code and clicked on the Extensions view icon in the Activity Bar (or press Ctrl+Shift+X).

2.	Search and Install Extensions:
o	I typed keywords (e.g., "Python", "GitLens") into the search bar and press Enter.

o	I clicked on the extension then clicked the "Install" button.

3.	Manage Installed Extensions:

o	Once installed, extensions can be managed from the Extensions view. They can be disabled, uninstalled, or updated them as needed.

Conclusion

Exploring and installing extensions in Visual Studio Code allows  tailoring the editor to suit  specific development needs. VS Code's extensive extension library offers solutions for various programming languages and workflows.







