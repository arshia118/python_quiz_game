# python Quiz Game
A simple Quiz Game Built with python


## Table of Contant 

- [Features](#features)
- [Table of Contant](#table-of-contant)
- [Project Structure](#project-structure)
- [Requuirments](#requuirments)
- [Installation](#installation)
- [Envoirment setup](#envoirment-setup)
- [Usage](#usage)
- [Example Output](#example-output)
- [Road Map](#road-map)
- [Cuntributing](#cuntributing)
- [Licence](#licence)
- [Author](#author)
  
## Features
- Quiz System
  - Asks the Player Multiple Question
  - Checks the answers automatically
  - Calculates the Final Score
- Result Storage
  - Sve Quiz Result in `result.txt`
- Admin mod
  - Asks for the admin password
  - Checks If the Password is Correct
  - Keeps the Private Information Out side of the Main Python file 
  - Loads the Admin Password from `.env`
  
## Project Structure
```txt
python_quiz_game/
│   main.py
│   question.py
│   Requuirments.txt 
│   .env.example
│   .gitignore
│   README.md


```
### File Discrebtion 
- `main.py` - Main File Used to run Quiz Game
- `question.py` - Stores Questions and Answers 
- `Requuirments.txt` - List the python packages needed for the project
- `.env.example` - Shows the Enviorment Variabels Needed by the Project
- `.gitignore` - Tells git  witch file snd folders should not be tracked 
- `README.md` - Contains the Project Documantation
## Requuirments
befor running hte Project Make sure you have :
- `Python 3`
- `Python-dotenv`
## Installation
1. open a terminal in the project folder 
2. check taht python installed:
``` bash
python --version
```
3. install the python packages:
``` bash
pip install -r Requuirments.txt
```
## Envoirment setup
1. create a `.env` file from `.env.example`
``` powershell
copy-item .env.example .env
```
2. open the new `.env` file
3. replace the example value with your password
``` txt
QUIZ_ADMIN_PASSWORD = your_password_here
```
4. save the file 
> do not commit your `.env` file  because it may contain private information 
## Usage
1. open a terminal in the project folder 
2. run the quiz game 
``` powershell
python main.py
```
3. chose `yes`or `no` for admin mod
4. if you chose `yes` enter the password from your `.enve` file
5. enter yourname 
6. answer the questions 
7. see your finall score and message 
8. your result is saved in `result.txt`

## Example Output
``` txt
do you want to open admin mod? yes/no no
whats your name ?arshia

welcome
what language are we using? python
correct

what command starts a git git init
correct

what command shows git status af
wrong

your score is : 2 out of 3
good job
```
## Road Map
- [x] Add multiple quiz question
- [x] calculate final score
- [x] save results to a file 
- [x] add admin mod 
- [ ] add more quiz questions 
- [ ] add dificalt levels
- [ ] add a timer 
## Cuntributing 

## Licence

## Author 
created by [arshia](https://github.com/arshia118)
