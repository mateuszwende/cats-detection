# cats-detection

- program written in python language
- program can recognize cats
- program uses tensorflow library
- program uses kaggle cat dataset

# setup

Requirements:

- python 3.7
- pip3
- virtualenv3 - to create isolated Python environments. virtualenv creates a folder which contains all the necessary executables to use the packages that a Python project would need. Tutorial: [https://docs.python-guide.org/dev/virtualenvs/](https://docs.python-guide.org/dev/virtualenvs/)

If you already have virtualenv installed in your working directory run this command: <br />
`virtualenv --system-site-packages -p python3 ./venv`

This will create virtual environment for your packages in the current directory and inherit from site-packages (manually built python packages).

To begin using the virtual environment, it needs to be activated run: <br />
`source venv/bin/activate`

Install all of the required dependencies run: <br />
`pip install -r requirements.txt`

To add new installed dependency update the `requirements.txt` file by running: <br />
`pip freeze > requirements.txt`
