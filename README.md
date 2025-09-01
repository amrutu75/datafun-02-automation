datafun-02-automation

Topic CC2.1 Start a Python Automation Project

A. Create New Repository


B. ALWAYS Use Git to clone the new repository to your local machine

git clone https://github.com/amrutu75/datafun-02-automation

C. Add .gitignore and requirements.txt



Task 1: Create new .gitignore file in repo and copy contents from https://github.com/denisecase/pro-analytics-01/

Task 2: Create new requirements.txt file in repo and copy contents from https://github.com/denisecase/pro-analytics-01/

D. To Update information from GitHub to VS Code

git pull

E.  Use Git to add, commit, and push your new files to GitHub


git add .
git commit -m "Add .gitignore"
git push -u origin main
git add .
git commit -m "Add requirements.txt"
git push -u origin main

E.  ALWAYS Create a Python Virtual Environment 

In VS Code, right click on the project folder, choose open in integrated terminal

To Create Virtual Environment

On Windows, Use Powershell:

py -m venv .venv

To activate a virtual environment

.\.venv\Scripts\Activate (


