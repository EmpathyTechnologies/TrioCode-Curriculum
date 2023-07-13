# Review

The command line interface is a way to talk to your computer by typing commands using just text. Imagine you have a magical text box where you can type special instructions, and the computer will do what you tell it to.

Instead of using buttons, icons, or pictures like you see in games or on websites, the command line interface uses words or short phrases as instructions. You type these instructions into a special program called a "terminal" or "command prompt."

Common command line instructions include:

- cd (change directory)
- ls (list)
- mkdir (make directory)
- rmdir (remove directory)
- rm (remove file)
- touch (create a file)
- clear (clears the command lines)

# Instructions

Let the first project begin!

# Step 1. Create a Project Folder

1. From your command line interface (the terminal or git bash), type in "cd ~"
2. If you haven't created a "code-projects" folder already, type in "mkdir code-projects" or if you already have the folder, type in "cd code-projects"
3. Create your first project folder "mkdir primary-emotions"
4. Change directories into that folder by typing in "cd primary-emotions"

- A directory is the same thing as a folder. It contains other folders and files.
- A file contains information or instructions, such as document.txt, image.png, or instructions.exe

5. A very common beginner mistake is being in the wrong location on gitbash. To verify you are in your code-projects folder, see the image below. If you can't see the photo, in the left-hand sidebar, right-click this activity file, and select "Open Preview".

<img width="500px" src="./assets/gitbash.png">

6. Create a folder inside of your primary-emotions folder called assets, by typing in "mkdir assets"
7. Create an index.html file by typing in "touch index.html"
8. Open your first project in VS Code by typing in "code ."
9. Inside of these instructions, find the images folder with the following images.

- anger.jpg
- contempt.jpg
- disgust.jpg
- fear.jpg
- happy.jpg
- sadness.jpg
- surprise.jpg

10. Download this images to your desktop, then drag and drop them onto VS Code into your project's images folder.

# Checkpoint 1

Your VS Code should look like the following.

<img width="500px" src="./assets/vscode.png">

#

11. The exclaimation point "!" is often called the "bang" symbol. Type in the bang symbol in the index.html file, then press enter. Your index.html file should now look like the following.

<img width="500px" src="./assets/vscode-exclamationpoint.png">

- The head section contains metadata. You don't need to know this right now.
- The body section section is what shows up on your website. You need to know this.

12. In between the body tags, type in `<div>Hello World</div>`

- A `<div>` is an HTML element used to create a division or section in a web page.

13. Beneath the `<div>Hello World</div>` add an image tag `<img src='./images/happy.jpg' alt="happy person" />`

- An alt property is to help people using a screen reader.

14. Add two more emotions to the page using image tags

You have now successfully completed an introduction to HTML pathing!
