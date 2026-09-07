# Using a Virtual Environment to resolve package version conflicts

Package version conflicts can become an issue when running Python's scripts on a local machine. 

One can solve this by creating a virtual environment to run Python's scripts that require packages.

A virtual environment is a directory which holds a Python Interpreter and a set of installed packages.

In many instances, there is a requirements.txt file that keeps track of the script's required packages.

Otherwise remove the third line below and install the packages manually by using '```pip install PACKAGE_NAME```'

Below are a set of commands to run a virtual environment on a local machine and install the dependencies.

Commands for Mac:
```
python -m venv venv
venv\Scripts\activate
python -m pip install -r .\requirements.txt
```

Commands for Windows:
```
python -m venv venv
venv\Scripts\activate
python -m pip install -r requirements.txt
```

Commands for Linux:
```
python3 -m venv venv
source venv/bin/activate
python -m pip install -r requirements.txt
```
