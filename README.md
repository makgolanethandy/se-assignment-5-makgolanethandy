[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15261294&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
     * Open web browser and navigate to https://code.visualstudio.com/.
     * On the homepage, click the download option on the right corner.
     * Chose option for Windows 10, 11 on the page
     * Once the download is done, run the installer and follow the on-screen instructions to 
       complete installation
     Note: On additional task prompts tick all the boxes under "Other"
     *Launch Visual code.

     Prerequisites (https://code.visualstudio.com/docs/supporting/requirements)
     * 1.6 GHz or faster processor
     * 1 GB of RAM
     
2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
 * Important extension added
    - Flutter-https://dartcode.org/
    - mplsstyle(Matplotlin)-
    -  Prettier-https://prettier.io/
    -  Python
    -  Code Runner
    -  Dart
    -  Flutter
    -  Pylance
    -  Python Debugger
    -  Python Image Preview
* Important settings
   - Go to file and activate "Autosave"

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
* Activity bar-allows us to switch between views and gives additional context-specific indicators
* Side Bar- Providesdeatiled information on the selected activity. Found on the left hand side
* Editor group- Allowas us to write and edit our codes in VS code.
* Status bar- Contains information about opened projects and files we are editing.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

* Command pallete-feature that lets you quickly access various commands in VS code and functionalities without navigating through menus.

* How to access it
   - Press Ctrl+Shift+P
* Common tasks that can be performed using Command palette
   - Add cuursor above
   - Adding cursor below
   - adding a line comment
   - Cleat editor history
   - Clear command histor

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
 * Role of extensions- Allow us to add new features, provide support to additional programmes installed, and to improve productivity
     - Extension can be found on the left side of VS code on the Activity bar
     - ![Screenshot 2024-06-22 053417](https://github.com/makgolanethandy/se-assignment-5-makgolanethandy/assets/171442187/5d2c3419-7a81-4e07-93e3-4052ea4d785e)
     - To install and manage Extensions: Click on Extension and click on the extension you want to 
       install and select install button.
     - Managing the extension can also be done throught the Extension view.
       - To list installed, Click the dropdownm menu on installed
       - To disable or uninstall extension, go to to the installed extension and select disable 
        option. ![Screenshot 2024-06-22 054358](https://github.com/makgolanethandy/se-assignment-5-makgolanethandy/assets/171442187/378098fa-bb1e-4547-93fb-6381c6173dcc)
     - Essenetial extensions for web development
       - Prettier

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

* Go to the top menu bar.
* Click on View.
* Select Terminal
* Select new terminal
* Navigate i the terminal window
   - allow you to run commands
   - create multiple terminal by click the plus icon in the terminal panel
   - or split terminal by clicking on the 'split terminal button'/ 'book icon

 * Advantages:
 - Allow for debugging and testing on the terminal
 - Allow for integrated tools within the terminal therefore reducing swtching between applications

8. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
  * to create or open folder
     - Open the Explorer panel
     - Select File
     - Select 'New file' to create a file, 'New folder' to create a new folder, 'Opne file' to open        existing file or 'Open folder' to open existing folder.
  * Navigate between between files and directories
    - Use the sidebar to navigate the directories and files structure quickly.    

9. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
     * Finding and customizing the setting
       - Go to top Menu bar
       - Select file
       - Followed by Preferences and then Settings
       - Under text editor- set you preferred font
       - Under workbench>Appearences> Set preferred theme
       - For keybindings: Top menu bar>file>preferences>key shortcuts
         
9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
   - Go to file Extension
   - Search python debugger
   - Install it
   - To start debug: Click run and debug on the side bar
                   - Open a python file
                   - Once file is open, Click where you want to set a breakpoint in the opened file
                    -Click run and debug
                   - Choose debug configuration 
                

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

*initializing a repository, making commits, and pushing changes to GitHub
 * Go to git and create a repository on Git
 * Copy the url linkof the repository
 * Navigate to run the below commands
   - git clone https://github.com/username/repository-name.git
   - cd repository-name
   - code. 
* It will take you to VS code
*Make your changes on VS code. Once done, run below command on VS code gitbash
- git add .
- git commit -m "commit message"
- git push 
   
 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

