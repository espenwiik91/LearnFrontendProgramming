# LearnFrontendProgramming
Path to setup dev enviroment to start learning frontend programming

## Visual Studio Code 
First we'll need a IDE (Integrated Development Enviroment). My suggestion is Visual Studio Code. It's a lightweight IDE highly popular among frontend developers.
To download Visual Studio Code follow the link bellow:


[VS Code Download](https://code.visualstudio.com/download)

## GitHub  ​
1. Create a github account

Github is a place where you can store your projects online. This is where you build up your portfolio.
2. Download git on your computer using the following link:

[GIT Download](https://git-scm.com/downloads)

Git is a version controll system that functions as a bridge between the local files on your computer and your online repository e.g. GitHub
3. Crate a new Github repository at github.com
A repository can be tought of as a project e.g. a webpage

4. Clone the newly created repository onto your local machin
This step will download the repository onto your local machine in a folder. It also serves as a connection between your local files and the online repository at GitHub
In order to complete this step. Follow the instructions below.

a. In your GitHub Repository, click the button that says "CODE". Copy the code from the drop down menu e.g. "https://github.com/espenwiik91/LearnFrontendProgramming.git"

b. Open Git Bash on your machine and navigate to where you would like to store the repository locally. 
  To navigate between folders in Git Bash use the following commands. 
  * cd <name-of-folder> -> Moves you to said folder. You can only navigate to folders that are childs of your current folder
  * cd .. -> Moves you to the parent folder of your current folder

c. Type the following -> git clone <https-link-to-your-repo> e.g. git clone https://github.com/espenwiik91/LearnFrontendProgramming.git

## Open VS Code
Now the repository is cloned to your local machine. Let's open VS Code:
Navigate into the newly downloaded folder and Open VS Code
```bash
cd <name-of-project> e.g. cd LearnFrontendProgramming
code .
```
This should open VS code in your current folder.

## Create a Javascript file and write some code
In VS Code's explorer tab you will see a README.md file. To create a new file, right click in the explorer tab and choose "New File". Name your file "HelloWorld.js". 

In the file, write the following code: 
```js
console.log("Hello World")
```
Save the file by hitting ctrl + s

## Upload new file to repository
Let's add this newly created js file to your GitHub repository.
* Open git bash. If your not in the project folder, navigate there now.
then execute the following commands:
```bash
git add .
git commit -m "uploading my first file
git push
```
The last command will prompt you to verify your account, simply choose the browser option.
Now go look in your GitHub repository and you should see your new file appear


