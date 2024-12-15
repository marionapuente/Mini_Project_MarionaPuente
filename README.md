# Mini Project Python Mariona Puente Quera

This is the Mini Project for the class: Advanced Python Concepts Workshop for Neuroscience.
It contains this readme file which has some basic explanations on how to set up the virtual environment on the first run if needed,
and on the last line it gives the instruction to install the project packages via the .toml file.

The project is in the file 'Miniproject.ipynb', I hope you enjoy it!

## On first run:
```bash 
#install Virtualenv is - a tool to set up your Python environments
pip install virtualenv
#create virtual environment (serve only this project):
python -m venv venv
#activate virtual environment
.\venv\Scripts\activate 
+ (venv) should appear as prefix to all command (run next command just after activating venv)
#update venv's python package-installer (pip) to its latest version
pip install --upgrade pip
#install project packages
pip install -e .[dev]     
``` 