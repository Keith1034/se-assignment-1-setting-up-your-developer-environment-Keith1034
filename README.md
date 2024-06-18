[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15290342&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

WHAT IS REQUIRED:
i.Windows installation media. This could be an installation ISO or DVD.
ii.USB flash drive with at least 5GB free space,ensure the flash disk has nothing important since it will be formatted.
iii.Technician PC - Windows PC that you'll use to format the USB flash drive
iv.Destination PC - A PC that you'll install Windows on

1st step - Format the drive and set the primary partition as active.
i.Connect the USB flash drive to your technician PC.
iiOpen Disk Management: Right-click on Start and choose Disk Management.
iiiFormat the partition: Right-click the USB drive partition and choose Format. Select the FAT32 file system to be able to boot either BIOS-based or UEFI-based PCs.
iv.Set the partition as active: Right-click the USB drive partition and click Mark Partition as Active.

2nd step - Copy Windows Setup to the USB flash drive.
i.Use File Explorer to copy and paste the entire contents of the Windows product DVD or ISO to the USB flash drive.
ii.Or either: add an unattend file to automate the installation process. For more information, see Automate Windows Setup.

Final step - Install Windows to the new PC.
i.Connect the USB flash drive to a new PC.
ii.Turn on the PC and press the key that opens the boot-device selection menu for the computer, such as the Esc/F10/F12 keys. Select the option that boots the PC from the USB flash drive.
iii.Windows Setup starts. Follow the instructions to install Windows.
iv.Remove the USB flash drive.



2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

i.Closely follow the on-screen instructions to download the installer.
ii.Run the downloaded installer.
iii.Choose the "Visual Studio" workload during installation, which includes the necessary components for general development.
iv.In the Visual Studio Installer, select the workloads and components you need based on your development requirements. Common workloads include ".NET Desktop Development" or "Web Development."
v.If needed, you can customize the installation by clicking on the "Individual components" tab in the installer and selecting or deselecting specific components.
vi.Click the "Install" button to start the installation process.This may take some time, as it involves downloading and installing the selected components.
vii.Once the installation is complete, launch Visual Studio.
viii.On the welcome screen, select your development environment. For example, you can choose "Development Settings" based on your preferred coding style.
ix.After all the steps are successfully accomplished,one can then start to code.


3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

Steps for installing Git:
i.Navigate to the latest Git for Windows installer and download the latest version.
iiOnce the installer has started, follow the instructions as provided in the Git Setup wizard screen until the installation is complete.
iii.Open the windows command prompt (or Git Bash if you selected not to use the standard Git Windows Command Prompt during the Git installation).
iv.Type git version to verify Git was installed.

Steps for installing Github:
i.Visit the download page for GitHub Desktop.
ii.Click Download for Windows.
iii.In your computer's Downloads folder, double-click the GitHub Desktop setup file.
iv.GitHub Desktop will launch after installation is complete.
v.Create a Github account


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

  i.When we click on the above link, it will bring us the following page.
 ii.Select the Python's version to download.
 iii.Click on the Install Now,double-click the executable file, which is downloaded;the following window will open.iv.Select Customize installation and proceed.
 v.Click on the Add Path check box, it will set the Python path automatically.


5. Install Package Managers:
   If applicable, install package managers like pip (Python).

 i.Download PIP get-pip.py. Before installing PIP, download the get-pip.py file. 
 ii.Installing PIP on Windows. To install PIP, run the following Python command: python get-pip.py. 
 iii.Verify Installation. 
 iv.Add Pip to Path. 
 v.Configuration.

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

i."Choosing a Setup Type" screen: Choose "Full" setup type. This installs all MySQL products and features. Then click the "Next" button to continue.
ii. "Check Requirements" screen: The installer checks if your pc has the requirements needed. If there is some failing requirements, click on each item to try to resolve them by clicking on the Execute button that will install all requirements automatically. Click "Next".
iii. "Installation" screen: See what products that will be installed. Click "Execute" to download and install the Products. After finishing the installation, click "Next".
iv. "Product Configuration" screen: See what products that will be configured. Click the "MySQL Server 8.0.23" option to configure the MySQL Server. Click the "Next" button. Choose the "Standalone MySQL Server/Classic MySQL Replication" option and click on the "Next" button. In page  "Type and Networking" set Config Type to "Development Computer" and "Connectivity" to "TCP/IP" and "Port" to "3006". Then, click the "Next" button.
v. "Authentication Method" screen: Choose "Use Strong Password Encryption for Authentication". Click "Next".
vi. "Accounts and Roles" screen: Set a password for the root account. Click "Next".
vii. "Windows Service" screen: Here, you configure the Windows Service to start the server. Keep the default setup, then click "Next".
viii. "Apply Configuration" screen: Click the "Execute" button to apply the Server configuration. After finishing, click the "Finish" button.
ix. "Product Configuration" screen: See that the Product Configuration is completed. Keep the default setting and click on the "Next" and "Finish" button to complete the MySQL package installation.
x. In the next screen, you can choose to configure the Router. Click on "Next", "Finish" and then click the "Next" button.
xi. "Connect To Server" screen: Type in the root password (from step vi). Click the "Check" button to check if the connection is successful or not. Click on the "Next" button.
xii. "Apply Configuration" screen: Select the options and click the "Execute" button. After finishing, click the "Finish" button.
xiii. "Installation Complete" screen: The installation is complete. Click the "Finish" button.


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

Installation of Prettier Code formatter on Visual Studio Code:
i.Open the Extensions tab and search for "Prettier - Code Format".
ii.Once you find it, click on the Install button to install it.
iii.You can also use the shortcut Ctrl + Shift + X to open the Extensions tab.
 
 I keenly followed all the setup procedures therefore I encountered no challenges in detting up my development environment.

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
