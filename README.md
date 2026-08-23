✅ To Create .gitignore file in VSCode
====================================
code .gitignore

✅ Step-by-Step Guide to Create .gitignore file in  (Windows PowerShell)
==========================================================================
1) Create a .gitignore file
Run this command in PowerShell:
New-Item .gitignore -Type File

2) Open .gitignore in VS Code
Run:  code .gitignore

3) Add node_modules to .gitignore
Inside .gitignore, add:
node_modules/

4) Check if node_modules is already tracked
Run: git rm -r --cached node_modules
This removes the folder from Git’s index (so it won’t be pushed), but keeps it locally.

5) Commit the changes
git add .gitignore
git commit -m "Ignore node_modules folder"

6) Push to GitHub
git push origin main

Notepad - In standard Windows Command Prompt (cmd.exe).
==========================================================
Run this command to open a blank file in Notepad, type your entries, and save: <br/>
notepad .gitignore <br/>





