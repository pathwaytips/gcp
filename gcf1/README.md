# Google Cloud Function Course

## This is help section to start project

To start a new project in Google Cloud, we can create it from Google Cloud Platform Console.
https://www.youtube.com/watch?v=q1muHEe38wg&list=PLLbwkQ_8LxVlzxsggFH6v53r_AZPWXyCQ

**1 Python Installation** 

https://www.python.org/downloads/

**2 Git Installation and Setup** 

https://git-scm.com/downloads

**3 Pycharm Installation and Git Setup** 

https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/
https://cloud.google.com/functions/docs/functions-framework

Installing pip (Windows) for other OS please follow instructions from above links

`py -m pip install --upgrade pip`

Installing virtualenv

`py -m pip install --user virtualenv`

Creating a virtual environment

`py -m venv env`

Activating a virtual environment

`.\env\Scripts\activate`

Leaving the virtual environment

`deactivate`

Installing packages

`pip install requests`
or (If specific version)
`pip install requests==2.18.4`

Using requirements files (My fav) create a requirements.txt file containing

`requests==2.18.4`

`google-auth==1.1.0`

Run to install above packages

`pip install -r requirements.txt`

Need Functions Framework lets you write lightweight functions that run in many different environments

https://cloud.google.com/functions/docs/functions-framework

