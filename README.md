# datafun-07-ml
Machine Learning project for Data Fundamentals Final

# .gitignore file
Ignore project virtual environment in the .venv folder
.venv/

Ignore Visual Studio Code settings in the .vscode folder
.vscode/

Ignore macOS specific files
.DS_Store

ignore checkpoints folder

 .ipynb_checkpoints/
Git commands used:
git pull
git add .
git commit 
git push
# Create and Manage virtual environment
py -m venv .venv

.venv\Scripts\Activate
# Import needed dependencies
Create a file in the root folder of your repo (same level as the README.md) named requirements.txt with the following packages:
jupyterlab
pandas
pyarrow
matplotlib
seaborn

Using following command to import packages:

py -m pip install -r requirements.txt