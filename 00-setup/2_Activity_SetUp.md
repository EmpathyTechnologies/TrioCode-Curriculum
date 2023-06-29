# Instructions

We will set up your computer with Git, Visual Studio Code (VSCode), Node.js, and GitHub.

# Step 1. Install Git:

Download the Git installer for Windows from the official website: https://git-scm.com/download/win
Run the downloaded installer.
Follow the installation wizard, selecting the desired options. The default settings are usually sufficient.
During the installation, you can choose the default editor for Git. Select "Use Visual Studio Code as Git's default editor."
Complete the installation process.

# Step 2. Install Visual Studio Code (VSCode):

Download the Visual Studio Code installer for Windows from the official website: https://code.visualstudio.com/download
Run the downloaded installer.
Follow the installation wizard, selecting the desired options. The default settings are generally suitable.
Complete the installation process.

# Step 3. Install Node.js:

Download the Node.js installer for Windows from the official website: https://nodejs.org
Choose the LTS (Long Term Support) version, which is recommended for most users.
Run the downloaded installer.
Follow the installation wizard, selecting the desired options. The default settings are usually appropriate.
Complete the installation process.

# Step 4. Install Git Bash for Windows:

Download the Git Bash for Windows installer from the official website: https://gitforwindows.org
Run the downloaded installer.
Follow the installation wizard, selecting the desired options. The default settings are typically suitable.
Complete the installation process.

# Step 5. Set up GitHub account:

Go to the GitHub website: https://github.com
Click on "Sign up" to create a new account if you don't have one. Otherwise, sign in to your existing account.
Follow the steps to create your GitHub account.

# Step 6. Configure Git with your GitHub account:

Open Git Bash (you can search for "Git Bash" in the Windows Start menu).
Set your name and email address for Git by running the following commands, replacing "Your Name" and "your_email@example.com" with your information:

- git config --global user.name "Your Name"
- git config --global user.email your_email@example.com

Authenticate Git with your GitHub account by generating an SSH key. Run the following command, replacing "your_email@example.com" with the email associated with your GitHub account:

- ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

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

# Verify Correct Installation

1. To verify git is correctly installed, in Git Bash enter the following command.

- git --version

If you see "git version 2.32.0" or a more updated version, then you set it up correctly.

2.  To verify node is correctly installed, in Git Bash enter the following command.

- node -v

Now you have Git, VSCode, Node.js, and a GitHub account set up on your Windows system. You can start using these tools for version control, code editing, Node.js development, and collaboration on GitHub.
