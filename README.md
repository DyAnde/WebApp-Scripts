# WebApp-Scripts
These are some scripts from Web App Development from Spring 2023.
___
**NOTE: A python installation of at least 3.11 is required**

Once the scripts are installed you will need to make them executable and place them in your `bin` directory.
For making them executable: `chmod 700 make*` **NOTE: This may be automatically done for you, use `ls -l` to view file perms**
To move to `bin`: `mv make* ~/bin/`

`makeflask` is the first script.
It creates a directory to be used as the root of the development environment for that Flask app it creates necessary subdirectories for Flask to run properly and creates an `app.py` with a simple home/index page.
It also has some extra things from WAD 2023 such as database integration.


`makehtml` is the second script.
It creates a template HTML page to be used by `app.py` in order to display a "proper" web page.


Feel free to modify these however you wish! [Here's a helpful Bash scripting cheat sheet](https://devhints.io/bash)
