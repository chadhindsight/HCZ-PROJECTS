# Python Project Ideas 
	- using turtle (animation etc)
	- game (Tic Tac Toe / rock/paper.sissor/ roll the dice ) 
	- build a website (using Flask) 


## Setting up a Python Project in Code spaces  

- for a python project use the "Blank" Template (for making either a game in turtle or pure python )
- for a python w/ Flask (for making a website) use "Flask" Template 


## Modeling Promise Academy 
- rhino (free) 3D modeling program 
- https://www.rhino3d.com/ 
- Rhino Tutorial : 3D Modeling: https://www.youtube.com/watch?v=AjyL1Z6t73A
- 3D Models of NYC https://www.nyc.gov/site/planning/data-maps/open-data/dwn-nyc-3d-model-download.page

## LIGHT SHOW 
- 3d cube 8x8x8 
- OLED boards (for animations in JS / Scratch) 
- custom light boards  

## SPEAKER 
- diy speaker (bluetooth can control from the board)

## Software
- ardino 
- raspberry pi 
- Python + JS web portal 
- login system 
- HTML / CSS styling 
- button for controlling board 


## Sys admin / security
- unix setting up the server on the raspberry pi 
- how to set up a firewall
- how to make sure it's secure 

## Scratch 
- animations 
- game 


# Scratch Project Ideas 
  - animation
  - game 

# Git Commands for Collaboration (Branching & Teamwork)

## Why is Branching Important?  
Branching allows multiple people to work on different features or fixes **without messing up the main code**. Each person works on their own copy (branch), and once their changes are ready, they merge them back.

---

## Basic Git Commands for Collaboration  

### 1. Create a New Branch (for a new feature or fix)  
```sh
git checkout -b new-branch-name
```
- This makes a copy of the main code so you can work separately.

### 2. Switch to an Existing Branch  
```sh
git checkout branch-name
```
- Use this when you want to move to another branch.

### 3. See All Branches  
```sh
git branch
```
- Shows the branches in the project.

### 4. Push Your Branch to GitHub  
```sh
git push origin branch-name
```
- Sends your branch (your work) to GitHub.

### 5. Get the Latest Code from GitHub  
```sh
git pull origin main
```
- Updates your local copy with the newest changes from others.

### 6. Merge Your Work into Main (After Approval)  
```sh
git merge branch-name
```
- Combines your branch into another branch (usually `main`).

---

## What is a Pull Request (PR)?  
- A **pull request** is a request to **merge** your changes into the main code.  
- Others review your code before it is added.  
- Created on GitHub, not in Git.

---

## Merge Conflicts (When Git Can’t Auto-Merge)  
- Happens when two people edit the **same** part of a file.  
- Git marks the conflict, and you **manually fix** it.  
- Then run:  
```sh
git add file-name
git commit -m "Fixed merge conflict"
```

---

## TL;DR  
- **Branches keep work separate** and help prevent mistakes.  
- **Pull requests let others review your code** before merging.  
- **`git pull` keeps you up to date** with changes.  
- **`git push` uploads your changes** to GitHub.  
- **Merge conflicts happen when two people edit the same thing**—fix them manually.
