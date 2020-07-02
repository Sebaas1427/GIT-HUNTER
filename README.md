# GIT-HUNTER
Python tool to detect critical information (passwords, usernames, strings connectios, etc) in public repositories. GITHUB Hacking.

## Installation
```
- git clone https://github.com/El-Palomo/GIT-HUNTER
- cd GIT-HUNTER
- python3 git_hunter.py -h
``` 

## Usage
-GIT-HUNTER script works with Python3.
```
usage: git_hunter.py [-h] [-f FILENAME] [-c COOKIE] [-d DIRECTORY] enterprise

A tool to get information of GIT Repository

positional arguments:
  enterprise            Name of enterprise to get repositories

optional arguments:
  -h, --help                            show this help message and exit
  -f FILENAME, --filename FILENAME      Github Dork FILENAME
  -c COOKIE, --cookie COOKIE            User_Session cookie to use --filename option
  -d DIRECTORY, --directory DIRECTORY   Folder to download repositories

Author: Omar Palomino (A.K.A - EL PALOMO) | elpalomo.pe
```
- Method 1: 
Only search in the REPOSITORY section of Github.
  1. Select an enterprise/organization in Github.
  2. You can use GIT-HUNTER with the following command:
    ```
    root@kali:~/GIT-HUNTER# python3 git_hunter.py -d /opt antamina
    ```


## Requirements


# Credits
