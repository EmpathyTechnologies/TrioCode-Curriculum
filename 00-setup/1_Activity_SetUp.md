# Instructions

We will set up your computer with Git, Visual Studio Code (VSCode), Node.js, and GitHub.

# Step 1. Install Git:

1. Go to https://git-scm.com/download/win (the official Git installer for Windows website)
2. Click "Click here to download" to download the installer
3. Click to open the downloaded installer
4. Click "Next" until you reach the "Install" button. Click "Install".
5. Open Git Bash
6. (optional) Recommend to pin Git Bash to the task bar or create a Git Bash icon on the desktop

We're hoing to have initial exposure to git (what we just installed) and git commands (things we type into the command line).
The expectation is exposure, not mastery.

- cd (change directory)
- ls (list)
- mkdir (make directory)
- rmdir (remove directory)
- touch (create a file)
- clear (clears the command lines)

WARNING: "rm -rf" is an extremely dangerous command. Do not use it unless you 100% know what you are doing.

When you open git bash, you should see an image liket this:

<img width="250px" src="../images/gitbash.png">

To verify git is correctly installed, in git bash enter the following command.

- git --version

You should see something like "git version 2.41.0.windows.1"

############

# Step 2. Install Visual Studio Code (VSCode):

1. Go to https://code.visualstudio.com/download (the official Visual Studio Code website)
2. Click to download the installer for your operating system (Windows, Linux, or Mac)
3. Click to open the downloaded installer
4. Click "Next" until you reach the "Install" button. Click "Install".

In git bash, type in "code ." to open VS-Code. You should see something like this.

<img width="250px" src="../images/gitbash.png">

# Step 3. Install Node.js:

1. Go to https://nodejs.org (the official Node.js website)
2. Click to download the current version installer "18.16.1 Recommended for Most Users"
3. Click to open the downloaded installer
4. Click "Next" until you reach the "Install" button. Click "Install".

Javascript is a coding language that websites run on.
Node.js is an open-source environment that allows you to run JavaScript code on the server, not just in web browsers.

To verify node is correctly installed, in Git Bash enter the following command.

- node -v

If you see "bash: node: command not found", we need to debug installation.

- Try closing your git bash (windows) / terminal (mac), then re-opening git bash / terminal (mac)
- Try uninstalling node, then reinstalling it

If you see something like "v18.16.1", then you successfully installed node.

# Step 4. Set up GitHub account:

1. Go to https://github.com
2. Click "Sign up" in the top right corner of the browser
3. Sign up

# Step 5. Configure Git with your GitHub account:

This will be a lot of things you don't need to know, but set up and do one time.

1. Open Git Bash
2. Set your name and email address for Git by running the following commands, replacing "Your Name" and "your_email@example.com" with your information:

- git config --global user.name "Your Name"
- git config --global user.email "your_email@example.com"

Authenticate Git with your GitHub account by generating an SSH key. Run the following command, replacing "your_email@example.com" with the email associated with your GitHub account:

- ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

1. Enter file in which to save the key
   press enter

2. Enter passphrase (empty for no passphrase)
   Your choice if you want a pass phrase. If you do choose to set up a passphrase, you will enter this frequently

Press Enter to accept the default location for the SSH key.
Enter a passphrase if desired (optional, but recommended for added security).
Run the following command to start the SSH agent:

- eval "$(ssh-agent -s)"

Add the generated SSH key to the SSH agent by running the following command, replacing ~/.ssh/id_rsa with the path to your SSH key:

- ssh-add ~/.ssh/id_rsa

Copy the SSH key to your clipboard by running the following command:

- clip < ~/.ssh/id_rsa.pub

Go to your GitHub account settings in a web browser.
Navigate to "SSH and GPG keys" under "Settings."
Click on "New SSH key" or "Add SSH key."
Give your SSH key a title and paste the copied key into the "Key" field.
Click on "Add SSH key" to save it.

# Step 6. Download the Google Chrome Browser

Now you have Git, VSCode, Node.js, and a GitHub account set up on your Windows system. You can start using these tools for version control, code editing, Node.js development, and collaboration on GitHub.
