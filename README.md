# Terminal

## Navigation

Open current directory in VS Code
ctrl + ~

list files/folder in current directory
$ ls

change directory
$ cd [folder]

make directory
$ mkdir [name]

create file
$ touch [filename]

crtl+L: clear terminal
ctrl+C: cancel running

## Git/GitHub

Git workflow
during project useage

add files to staging area
$ git add [file.ext]
$ git add .

commit files
$ git commit -m "message here"

Update project source
$ git push

Branching
$ git branch - view branches
$ git branch -a  - view remote branches
$ git checkout -b [branch name] - creates a branch
$ git checkout [branch name] - opens an existing branch. Can be a remote branch.

Merge
$ git merge [branch] - merge branch into current branch

----------------------------

View change log
$ git log

Check for new files (doesn't DL)
$ git fetch
Check for new files & DL
$ git pull

----------------------------

Git project set-up (join existing project)

$ git clone [url]

Git project set-up (create new project):

setup git repo in location
$ git init

add files to staging area
$ git add [file.ext]
$ git add .

commit files
$ git commit -m "initial project commit"

Initial project commit (GitHub)
  create repo at GitHub
  then run:
$ git remote add origin [project url].git
$ git branch -M master
$ git push -u origin master

Ref:
https://github.github.com/training-kit/downloads/github-git-cheat-sheet/



## Node/NPM

Node:
$ node --version

NPM
$ npm --version

NVM-windows

$ nvm ls
$ nvm use <version>

$ nvm list available
$ nvm install <version>

Install nvm: https://github.com/coreybutler/nvm-windows

## Python/pip

Python
$ python -V

Package manager - pip
$ pip -V

$ pip list

pip package requirements & install
https://note.nkmk.me/en/python-pip-install-requirements/


venv - virtual environment
  create a local environemnt (called env in current folder)
$ py -m venv env

  activate the environment
$ env\Scripts\activate 
  Select your new environment by using the Python: Select Interpreter command from the Command Palette.
$ deactivate

NOTE: setting the project interpreter to the venv, it will be auto activated

  select pylint

https://code.visualstudio.com/docs/python/environments


## Django


Run Django dev server
$ python manage.py runserver

Shell
$ python manage.py shell

Migration (models)
$ python manage.py makemigrations [app name]
$ python manage.py migrate

-----
set-up

Set-up to venv
$ py -m venv env

Install
$ pip install Django

Check Version
$ python -m django --version


## Flask


Run the app
$ flask run

Set dev mode
$ export FLASK_ENV=development (Bash)

-----
set-up

Install to venv
$ py -m venv env

Flask
> pip install Flask
https://flask.palletsprojects.com/en/1.1.x/installation/#installation

Flask-session
> pip install Flask-Session
https://flask-session.readthedocs.io/en/latest/


## Firebase

  Need to relearn


## Sass/scss


npm install -g sass
sass --version

Convert scss to css
Manually
$ sass style.scss:style.css
Watch files
$ sass --watch style.scss:style.css
Watch folders
$ sass --watch app/style.scss:dist/style.css


## Other


gulp (global)
$ gulp --version

yarn (global)
$ yarn --version

====================================
====================================
