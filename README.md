ok here's just sum rules for this repo 

repo: basically an online library to hold any shared scripts that we use for everyone/can used by anyone in here. github basically makes it possible to edit/build scripts at the same time within a group, everyone can make changes and it'll update in real time. 

codespace: this is genuinely like a virtual desktop, by using codespace you DO NOT have to download VSC, python, etc the entire workspace is developed for you where you can work from a browser and the entire desktop is set up for you. if you DO NOT WANT TO download python, VSC and set everything up, you can use the codespace on here. Each codespace will be for each diff project we decide to use python for, so one per script. for each codespace just be diligent to make your own individual branches from the main branch/script, so we can make changes, edits and additions without changing the master code/script unknowningly (just code etiqutte). 

somethings to note for shared scripts: 
1. branches: branches are basically an individual ver / clone of a script where you can make changes without hurting the main branch/repo. if you want to finalize your changes to a certain script to the main branch, you can merge your version with the version stored on the main branch (repo). 
2. merge conflicts: sometimes when editing the same script, sometimes there are conflicting changes made on a certain part of a script. when that happens we will get a notif from github asking to resolve it

so it's kind of like a tree. the trunk is the MAIN BRANCH, think of it as the final version that we all have access to and share. but we can creare our own individual branches where we can make changes, add features, and delete unecessary lines. MERGING is moving from our individual branch where we make changes, to the trunk, the finalized version of the code. Consider this shared repo, the main/master branch.

3. commits and pushes: you're going to want to save from your local computer to the branch you're working from on git. commits are basically saves to YOUR local drive, meaning that we cannot see it. PUSHES are "pushing" your changes from your local drive to the online branch you have for this repo.

4. Pull Requests: a way to review and discuss code changes before marging them to the main branch. we can make comments, deny/approve, and look at the changes being made in real time.

DOWNLOADING AND SETTING UP PYTHON. 
1. Download VS code: https://code.visualstudio.com/download?_exp_download=fb315fc982
2. Download python: https://www.python.org/downloads/release/python-3147/ (macOS + windows ver. below scroll down) 
3. When you open VSC, you can customize the layout on the top right, first icon to the right of the blue "Update" button
4. Go to the left and go to the "Extensions" tab, download "Python" and "Python Debugger"
5. Go to the extension and press activate or wtv it says just enable the extensions you downloaded
6. if you get a notif like "python not found", fret not. close VSC and reopen and VSC should be able to find the file now.
  6.1. TO CHECK: go to your terminal (output window at the bottom) and type: WINDOWS: py --3 version | macOS: python3 -- version
  6.2 the output should be the version of python you have installed + enabled on VSC. IF YOU GET, "python not found" then VSC is still not detecting your python download file (ill help you best i can if this happens)
7. ok now you're going to create a virtual environment (venv). virtual environments are isolated workspaces so you can use online python libraries without having to download all python libraries to your drive (saves space      and prevents conflicts between library versions).
   7.1 go to the search bar at the top and type: ">python" and press "create virtual environment"
   7.2 just press quick create and VSC will basically create the environment for you - for your first environment, it'll prompt you to make a folder, name it, etc and in the future when you make new environments you can use        that same folder and you won't have to make a new one.
   7.3 now in your terminal, it should say "(.venv)", example: (.venv) PS C:\Users\jtrang\Python> -- this is what it says in my terminal once your environment is created
   7.4 use "pip install" to install any libraries needed for this code.
