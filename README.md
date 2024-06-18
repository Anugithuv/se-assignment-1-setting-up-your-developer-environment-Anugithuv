[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15278270&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   Step 1: Go to Windows 11 download page and click on Download Now under the ‘Create Windows 11 Installation Media’ section.
   Step 2: A ‘Windows 11 Setup’ window will greet you with the ‘Applicable notices and license terms.’ Read the terms and click on Accept to proceed.
   Step 3: Select the language and the Windows edition of your choice that you want to install. Once done, click on the Next button.
   Step 4: Select the USB flash drive option on the next screen and click the Next button.Note: The USB Drive must be formatted and be of at least 5GB.
   Step 5: Select the drive corresponding to the USB flash drive and click the Next button.
   Step 6: The Media Creation Tool will download Windows 11 onto the USB drive.
   Step 7: After the download and installation process, you will see a message that says, ‘Your USB flash drive is ready’. Click on the Finish button.


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   Step 1: Download the Installer
      First, head over to the official Visual Studio Code website.Visit the website and look for the download button. Click on it, and make sure you select the version that’s compatible with Windows 11. The download should start automatically.
   Step 2: Run the Installer
      After the download completes, open the installer file.Locate the downloaded file in your Downloads folder. It should be named something like "VSCodeSetup.exe". Double-click on it to start the installation process.
   Step 3: Accept the License Agreement
      Next, accept the terms and conditions by checking the box and clicking "Next".You’ll be presented with a license agreement. It’s important to read through this to understand your rights and obligations. Once you agree, proceed to the next step.
   Step 4: Choose Installation Location
      Select the folder where you want Visual Studio Code to be installed, then click "Next".By default, it will suggest a directory. If you’re fine with that, just proceed. Otherwise, choose a different location on your machine.
   Step 5: Select Additional Tasks
      add PATH to allows you to open it from the command line.
   Step 6: Install
      Click "Install" to begin the installation process.
      Launch Visual Studio Code.Once the installation is complete, check the box to launch Visual Studio Code, then click "Finish".
   
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.
   
   STEP 1:Download Git:
      Go to the official Git download page.
      Download the installer for Windows.
   STEP2:Run the Installer:
      Open the downloaded .exe file.
      Follow the installation wizard:
      Adjusting your PATH environment: Select "Use Git from the Windows Command Prompt".
      Choosing the SSH executable: Select "Use bundled OpenSSH".
      Configuring the line ending conversions: Select "Checkout Windows-style, commit Unix-style line endings".
      Choosing the terminal emulator to use with Git Bash: Select "Use Windows' default console window".
      Accept the default options for the rest or customize as needed.
   STEP3:Verify Installation:
      Open Command Prompt or Git Bash.
      Type the following command to check the installed version:
         git--version   
   STEP4:Sign Up for GitHub:
      Go to GitHub's website.
      Click on Sign up.
      Fill out the form with your details (username, email, password).
      Complete the verification and click Create account.
   STEP5:Verify Email:
      Check your email for a verification message from GitHub.
      Click on the verification link in the email to verify your email address.
   STEP6:Run the following commands:
      git config --global user.name "Your Name"
      git config --global user.email "your.email@example.com"

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  
   step1:Visit the Python Website:Open your web browser and go to Python's official website.Download the Installer.Navigate to the Downloads section then click on download
   step2:Run the Installer:Open the downloaded .exe file and follow the installation wizard.
   step3:Install Python:Select the installation location and click Install.
   step4:Verify Installation:Open Command Prompt or Git Bash.Type the following command to check the 
   installed version:python --version


5. Install Package Managers:
   If applicable, install package managers like pip (Python).

   Step 1: Download get-pip.py
      Open your web browser.
      Go to the official get-pip.py script page: get-pip.py.
      Right-click on the page and select "Save As" to save the file as get-pip.py.
   Step 2: Install pip
      open your file expoloere and Navigate to the folder where get-pip.py is saved.
      Then open your git bash and navigavte to where it is saved
      And inside the directory run python get-pip.py to intall pip
   Step 3:Step 5: Add pip to PATH (if necessary)
      Open the Start menu and search for "Environment Variables."
      Select "Edit the system environment variables."
      In the System Properties window, click the "Environment Variables" button.
      Under "System variables," scroll down and select the Path variable. Click "Edit."
      Click "New" and add the path to your Python Scripts directory (e.g., C:\Users\YourUsername\AppData\Local\Programs\Python\Python39\Scripts).
      Click "OK" to close all dialog boxes.
   Step 4: Verify pip Installation
      Open Command Prompt or Git Bash.
      Type the following command to check the installed version: pip --version
   Step 5: Install necessary packages
      Install necessary packages using pip install command. to install numpy, run: pip install
      numpy
   Step 6: Verify package installation
      Open Command Prompt or Git Bash.
      Type the following command to check the installed package: python -c "import numpy; print(numpy
      .version.version)"


   

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

   step1:Download MySQL Installer
      Visit the MySQL Installer Page
      Download the MySQL Installer
   Step2:Run the MySQL Installer
      Run the Installer:Once the download is complete, locate the installer file (usually named something like mysql-installer-community-5.7.x.x.msi) in your Downloads folder and double-click it to run the installer.
      Setup Type:The installer will prompt you to choose a setup type. The available options are:
      Developer Default,Server only,Client only,Full,Custom.Select Developer Defaultto install all MySQL products and features. Click Next.
      Check Requirements:The installer will check for any required software. If anything is missing, it will prompt you to install them. Click Execute to install the required software.
      Installation:The installer will show the list of products to be installed. Click Execute to begin the installation process.Once the installation is complete, click Next.
   Step3:Configure MySQL Server
      Product Configuration:The installer will proceed to the configuration phase. Select Next to start configuring the MySQL server.
      Type and Networking:Select the configuration type (usually Development Machine for local development).Leave the default settings for TCP/IP and port 3306 unless you have specific requirements.Click Next.
      Authentication Method:Choose the authentication method. Use Strong Password Encryption is recommended.Click Next.
      Accounts and Roles:Set a strong root password and create any additional user accounts if needed.Click Next.
      Windows Service:Configure MySQL to run as a Windows service.Leave the default settings and ensure "Start the MySQL Server at System Startup" is checked.Click Next.
      Apply Configuration:Review the configuration settings and click Execute to apply the configuration.Once the configuration is complete, click Finish.
   step4: Verify Installation
      Open MySQL Workbench:If you installed MySQL Workbench, open it from the Start menu.
      Connect to the MySQL server using the root account and the password you set during the installation.
7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
   

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

   Step 1: Open Visual Studio Code
      Launch VS Code:Open Visual Studio Code from your applications or start menu.
   Step 2: Access the Extensions Marketplace
      Open Extensions View:Click on the Extensions icon in the Activity Bar on the side of the window. This icon looks like four squares.Alternatively, you can open the Extensions view by pressing Ctrl+Shift+X on Windows/Linux or Cmd+Shift+X on macOS.
   Step 3: Search for Extensions
      Search for Extensions:In the Extensions view, there is a search bar where you can type keywords to find specific extensions.
      Some common types of extensions you might want to install include:Syntax Highlighting: Provides color coding for various programming languages.Linting: Identifies and reports errors in your code.Code Formatting: Automatically formats your code according to predefined rules.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

MY GITHUB REPOSITORY LINK: https://github.com/Anugithuv/PlpAssignmentproject


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
