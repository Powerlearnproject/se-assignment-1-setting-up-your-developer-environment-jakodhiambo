[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15287177&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
Visit Windows 11 Download.
Click on "Download now" to get the installation assistant.
Run the installation assistant and follow the on-screen instructions.
If you encounter issues:
Ensure your PC meets the minimum system requirements for Windows 11.
Check for updates and install any necessary drivers.
Disable any third-party antivirus software during the installation process.

3. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

Visit Visual Studio Code Download.
Choose the appropriate version for Windows and download the installer.
Run the installer and follow the setup wizard.
Customization:
During installation, you can select additional tasks such as creating a desktop icon and adding VS Code to the context menu.
After installation, you can customize the appearance (theme, icons) and settings (auto-save, font size) in the settings menu (File > Preferences > Settings).
5. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

Install Git
Visit Git Downloads for Windows.
Download the installer and run it.
During installation, select the following options for a smooth setup:
Use Git from Git Bash only.
Use the OpenSSL library.
Checkout as-is, commit as-is.
Use Windows' default console window.
Configure Git
Open Git Bash and configure your username and email:
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
Check your configuration with:
git config --list
Create a GitHub Account
Visit GitHub and sign up for a new account.
Initialize a Git Repository
Create a new directory for your project:
mkdir MyProject
cd MyProject
Initialize Git in this directory:
git init
Make Your First Commit
Create a README file:
echo "# MyProject" > README.md
Add and commit the file:
git add README.md
git commit -m "Initial commit"
Push to GitHub
Create a new repository on GitHub.
Link your local repository to GitHub:
git remote add origin https://github.com/yourusername/MyProject.git
git branch -M main
git push -u origin main
Troubleshooting:
Ensure you have internet connectivity.
If you encounter authentication issues, consider using SSH keys for secure access.

6. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  4. Install Necessary Programming Languages and Runtimes
Install Python
Visit Python Downloads.
Download the latest version of Python.
Run the installer, and ensure you check the box to add Python to your PATH during installation.
Verify the installation:
python --version
pip --version
Troubleshooting:
If python or pip commands are not recognized, check your system PATH environment variable to ensure Python's installation directory is included.

7. Install Package Managers:
   If applicable, install package managers like pip (Python).
Install pip (Python)
Pip is installed by default with Python 3.4+.
Verify the installation:
pip --version
8. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

Visit MySQL Installer Downloads.
Download and run the MySQL Installer.
During installation, select "Server only" if you do not need the full MySQL suite.
Configure MySQL:
Set a root password and create any additional user accounts as needed.
Allow MySQL to start at system startup if desired.
Verify the installation:
mysql --version
Troubleshooting:
Ensure MySQL service is running (services.msc).
Check firewall settings to ensure MySQL ports are open.
9. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
Install Docker
Visit Docker Desktop Download.
Download and run the Docker Desktop installer.
Follow the setup wizard, and start Docker Desktop.
Verify the installation:
docker --version
Troubleshooting:
Ensure virtualization is enabled in your BIOS.
Check Docker's settings to allocate sufficient resources (CPU, memory).
10. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
Visual Studio Code Extensions
Open Visual Studio Code.
Go to the Extensions view by clicking the Extensions icon in the Activity Bar or pressing Ctrl+Shift+X.
Install desired extensions such as:
Python: For Python development.
GitLens: Enhances Git capabilities.
Docker: Integrates Docker support.
Prettier - Code formatter: Ensures consistent code formatting.
ESLint: Provides JavaScript and TypeScript linting.


11. Document Your Setup:
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
