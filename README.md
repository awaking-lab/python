Package version conflicts can become an issue on a local machine. 

One should create a virtual environment to run Python Scripts that require packages.

A virtual environment is a directory which holds a Python Interpreter and a set of installed packages.

In many instances, there is a requirements.txt file that keeps track of the script's required packages.

Below are a set of commands to run a virtual environment on a local machine.

Commands for Mac:
```
python -m venv venv
venv\Scripts\activate
python -m pip install -r .\requirements.txt
```

Commands for Windows:

Commands for Linux:
