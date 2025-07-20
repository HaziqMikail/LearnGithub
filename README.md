# Demo

This my for Github learning!

Hello world!  
10/7/2025

---

## command

cd LearnGithub          navigate  
ls -la                  view all file  
git status              check status  
git add .               stage all changes for commit  
git commit -m           save changes  
git push                send to github    
git init                create new repo  
git remote -v           Lists all remotes for local Git repository  
git push origin master  Pushes local master branch to the origin remote  
git remote add origin   Adds remote called origin pointing toGitHub repo  


---

## Add folder to repo

:: Step 1: Go to your project folder
cd "C:\Users\Mikail\Documents\NetBeansProjects\YourProjectFolder"

:: Step 2: Initialize Git in this folder
git init

:: Step 3: Connect to your GitHub repository
git remote add origin https://github.com/your-username/Portfolio.git

:: Step 4: Stage all files for commit
git add .

:: Step 5: Commit with a message
git commit -m "Add YourProjectFolder files"

:: Step 6: Set the main branch (if not already)
git branch -M main

:: Step 7: Push to GitHub
git push -u origin main

---


## In folder

git add "TicTAcToe - Minimax"  
git commit -m "Update TicTAcToe - Minimax project"  
git push origin main    

git pull origin main --allow-unrelated-histories

if in Vim  
1) D  
2) :wq  
