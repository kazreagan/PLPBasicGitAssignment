# PLPBasicGitAssignment
Task 1: Repository Setup

Open Github on your machine and log into your account

click your profile icon in the top-right corner of your screen

from the drop-down menu, select the "Your repositories" option

once this opens up, click the button labeled "New"

input your required Repository name, Description(optional)

choose the visibility of your repository (Public or Private)

in this case initialize your repository with a README file

at this point we can ignore the other selectibles and click the "Create Repository" button at the bottom.

Task 2: Local Setup
Local Folder Setup:

on your machine, navigate to your desired disk partition(D:, E:, or F:)

right click in a blank space in the chosen partition and from the pop_up menu, navigate to the "New" option and from the side-menu, choose "Folder"

Name it as required(in this case "PLPBasicGitAssignment") and press "ENTER" on your keyboard

From your Windows menu, navigate to Git Bash, right_click on it and choose "run as administrator"

once it opens, navigate to the previously created folder by punching in the command:
    cd "partition where you created the folder", hit the "Enter" button on your keyboard

    cd "name of the folder(in this case which is PLPBasicGitAssignment)", hit the "Enter" button on your keyboard and there you are inside the folder

Git Initialization:
Initialize a new Git repository in the local folder(PLPBasicGitAssignment) by typing the command
    git init

Connecting to Github

head back to your Github and open the repository you created and copy its URL from the search bar of your favorite browser.

Now head back to the bash terminal and type the command;
    git remote add origin "paste the URL of the repository that you copied earlier"

Task 3: Making Changes 

Create a File;
in your Gitbash terminal type the command
    code .
this will open a code editor(Visual Studio code)

once it opens, hover over the name of your previously created folder and choose the "New File" option from the little icon
-list that pops up

name it (Hello.txt) and hit "Enter" to open it and while inside it, type the text "Hello, Git!"

Committing Changes:
staging the changes;
open your bash terminal and type the command
    git add .
this will add all the changes you made to the repository

commit changes;
once a new line is activated, type the command
    git commit -m "Add hell.txt with a greeting"

Task 4: Pushing to Github
Pushinf to Github;
once the commit command is successful, on a new line type the command
    git push -u origin main
this will push all the changes you made to your local repository into the repository you created on GitHub

Task 5: Verification
head back to your browser and open your repository again, at this point you must be able to see all the changes if at all you did evrything right.

NOTE:
    commiting and pushing changes requires a stable internet connection and your Visual Studio Code editor must be linked to your Github account.