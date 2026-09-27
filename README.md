# Python Quize Game
![Static Badge](https://img.shields.io/badge/python-3.12-blue)
## Table of contents
  
- [Features](#features)  
- [Project Structure](#project-structure)  
- [Requirments](#requirments)
- [Installarion](#installarion)
- [Envoirment Setup](#envoirmentSetup)
- [Usage](#usage)
- [Roadmap](#roadmap)
- [Screan shot](#screan-shot)
- [Contributing](#contributing)
- [Licence](#licence)
- [Author](#author)

## Features
-   Quiz System

    - Ask the player multiple question
    - Checks the answer automaticlly
    - Calculates the final score
- Resulte storage
    - Saves quize results in `result.txt`
- Includes an admin mode 
    - Asks for the admin password is correct
    - Checks if the password is correct
    - Keeps the private information outside the main python file
    - loads the password from `.env`

    


## Project Structure
```text
python_quiz_game/
│   .env.example
│   main.py
│   question.py
│   README.md
│   requirements.txt
├───gifts
│       quiz_demo.gif
├───pictures
│       1.png
│       2.png
│       3.png
└───
```
### File Description 
| file | description | 
| --- | --- | 
| ` main.py ` | main file used to run quiz game |
| `  question.py ` | stores questions and answers |
| `requirements.txt` | lists the python packages needed for the project. |
| `.env.example ` | shows the envoiment variables needed by the project |
| `.gitignore ` | tells git which files and folders shold not be tracket |
| `.README.md ` | contains  the project documentation |
| `pictures/ ` | stores project screenshots |   
| `pictures/1.png ` | screenshot of the game start |
| `pictures/2.png ` | screenshot of the quiz section |
| `pictures/3.png ` | screenshot of the finall result |
| `gifes/ ` | stores demo GIF files |
| `gifes/quiz_demo.gif ` | shoes the project demo |

## Requirments
before runing the project make sure you have:
- `python 3`
- `python-dotenv`
## Installation
1. open a terminal in the project folder.
2. check that python is installed :
```bash
python--version
```
3. install the python packages:
```bash
pip install -r requirements.txt

```
## Envoirment Setup
1. create a `.env` file from `.env.example`:
```bash
cp .env.example .env
```
2. Open the new `.env` file
3. Replace the example value  with your own password
```text
QUIZ_ADMIN_PASSWORD=your_password_here
```
4. save the file.
> do not commit your `.env` file becuase it may contain private information

## Usage
1.  Open a terminal in the project folder
2. Run the quiz game
```bash
python main.py
```
3. Choose `yes` or `no` for admin mode
4. If you choose `yes` enter a pssword from your `.env` file
5. Enter your name
6. answer the question
7. see your finall score ans message
8. your result is saved in `result.txt`1
## Example Output
```text
do you want to open admin mode? yes/no: no
whats your name?maria
welcome
what language are we using?python 
correct
what comand start a git?git init
correct
what comand shows git status?git status
correct
your score is:  3 out of 3
excelient job maria
```
## Screan shot
### start game
![Start game](pictures/1.png)
### Quiz
![quiz](pictures/2.png)
### Final score
![final score](pictures/3.png)
## Demo
![quiz game demo](gifts/quiz_demo.gif)
## Roadmap
- [x] add multiple quize question
- [x] calculate the final score
- [ ] add admin mode
- [ ] save results to a file
- [ ] add multiple quize question
- [ ] add more quiz questions
- [ ] add difficultly levels
- [ ] add a timer
## Contributing

## Licence

## Author
create by [helia](https://github.com/heliya-babaie-sh)