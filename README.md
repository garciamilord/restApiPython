# restApiPython

# Create an environment #

Create a project folder and a venv folder within:

## macOS/Linux ##
$ mkdir myproject
$ cd myproject
$ python3 -m venv venv

## Windows ##
> mkdir myproject
> cd myproject
> py -3 -m venv venv

# Activate the environment #

Before you work on your project, activate the corresponding environment:

## macOS/Linux ##
$ . venv/bin/activate

## Windows ##
> venv\Scripts\activate

Your shell prompt will change to show the name of the activated environment.

# Install Flask #

Within the activated environment, use the following command to install Flask:

$ pip install Flask




Run locally


curl -i -H "Content-Type: Application/json" -X PUT  http://localhost:5000/artists/1

curl -i -H "Content-Type: Application/json" -X POST http://localhost:5000/artists

curl -i -H "Content-Type: Application/json" -X DELETE  http://localhost:5000/artists/1 
