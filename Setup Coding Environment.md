# Setting Up Your Coding Environment
# I created this to remind me how I set up vs code on my computer; i wanted vs code to be able to use github copilot with the SAP API work that we did at work.  The highlighted text below are the important points; the rest was filled in by copilot

## 1. Install a Code Editor
- Download and install a code editor like Visual Studio Code, Sublime Text, or IntelliJ IDEA.
- **I downloaded WinPython slim version**
- **Then I downloaded vs code zip edition and got a subscription for github copilot.**
- **I extracted vs code into the "t" folder in winpython folder. into a subfolder called "vscode"**
- **you have to then tell vs code where to find the python interpreter which is python.exe.**
- **you also have to add the python folder and script folder to your windows path locations in advanced system settings. more on this below in "configure your environment"**
- **vs code lets you log into github and sets up your github copilot automatically**

## 2. Install a Version Control System
- Install Git from [https://git-scm.com/](https://git-scm.com/).
- Install notepad++ and use it as your editor
- Configure Git with your name and email:
    ```
    git config --global user.name "Your Name"
    git config --global user.email "your.email@example.com"
    ```
- You'll also need to get a token from github so you can push changes.
- At this point, you can clone a repository to your local machine
- **When you open vs code and open a git repository, it automatically connects through git and recognizes the depository**

## 3. Install a Programming Language
- Choose a programming language and install its runtime or compiler:
    - Python: [https://www.python.org/downloads/](https://www.python.org/downloads/)
    - Node.js: [https://nodejs.org/](https://nodejs.org/)
    - Java: [https://www.oracle.com/java/technologies/javase-downloads.html](https://www.oracle.com/java/technologies/javase-downloads.html)
    - **I installed python plug in through vs code**

## 4. Set Up a Package Manager
- Python: Install `pip` (comes with Python) and optionally `virtualenv`.
- Node.js: Use `npm` (comes with Node.js) or `yarn`.
- Java: Use `Maven` or `Gradle`.
- **So pip alrady comes with winpython if you installed that in step 1**

## 5. Install Additional Tools
- Install a terminal emulator (e.g., Windows Terminal, iTerm2).
- Install Docker if you need containerization: [https://www.docker.com/](https://www.docker.com/).
- I don't know what this is

## 6. Configure Your Environment
- **Set up environment variables (e.g., `PATH`). you'll need to add the file path where python and pip**
- **Run SystemPropertiesAdvanced, go to Environment Variables, find Path under System Variables,edit and add the two file paths.  you need this to run python code from the terminal in vs code.  you don't need to do this if you just run scripts**
- Create a workspace directory for your projects.

## 7. Test Your Setup
- Verify installations by running version commands:
    ```
    python --version
    node --version
    git --version
    ```
- Create and run a "Hello, World!" program in your chosen language.

## 8. Optional: Install Extensions and Plugins
- For Visual Studio Code, install extensions for your language (e.g., Python, Prettier, ESLint).
- Set up linters and formatters for code quality.

## 9. Learn and Explore
- Familiarize yourself with the tools and their documentation.
- Start coding and building projects!