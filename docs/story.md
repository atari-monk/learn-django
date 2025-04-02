# Story

2025-04-02
---

## Objective

- I want to learn django.  
- Write automation scripts.  

## Project Tree

See structure and keep it simple but organized.

```plaintext
C:\atari-monk\code\learn-django
├── docs
│   └── story.md
├── index.md
└── script
    └── setup_django.py
```

## Setup django

- I need a script 'setup_django.py' that will:
- check if framework is installed
- print version if it is
- ask to update and update if user wants to
- install if not installed
- it needs to be able to be run any time and in bigger script when framework needs to be checked

## They way of using scripts

- This is very important
- In root folder is script folder
- I run scripts with
```sh
 python .\script\setup_django.py
```
- cleaing console with
```sh
cls
```
- Many a times i wrote wrappers with menus to run scripts
- This run script wrappers made me loose the plot every time
- DONT DO THEM UNLESS MUCH LATER AT MATURITY OF SCRIPTS