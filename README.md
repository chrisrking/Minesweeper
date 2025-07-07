# Minesweeper Solver Bot (Python + Selenium)

The goal of this project is an automated bot that plays the beginner board on [minesweeper.online](https://minesweeper.online) using 
rule-based logic. The bot clicks and flags tiles using the same logic a human would apply — no random guessing unless necessary. 
It restarts automatically after a loss and continues until it wins.

---

Status: The random version will play minesweeper by selecting random squares until it either loses or wins. Losing causes it to restart and keep trying. Winning will stay on the screen for a limited time before closing. 
The AI version that is meant to play like a human is currently under maintenance. The flag feature will often get stuck in a loop and never finish the game.

---

## Requirements
Currently works on Python 3.x (My version is 3.13.3)

## Installs
pip install selenium
    pip install --upgrade selenium
    
May need to download ChromeDriver v137 if your current version does not work.
