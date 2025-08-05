# devsecops-tasks-girishn-2nd
devsecops-tasks-girishn-2nd
# DevSecOps Git Practice - Girish N
## Date: 2025-08-04

### 🔧 Git Configuration
git config --global user.name "Girish N"
git config --global user.email "girishn9@gmail.com"
git config --list

### 📁 Repository Setup
git clone git@github.com:girishn9/devsecops-tasks-girishn-2nd.git
cd devsecops-tasks-girishn-2nd
mkdir 04-08-2025-2nd
cd 04-08-2025-2nd
touch task3.txt task4.txt

### 📦 Staging and Committing
git status
git add .
git commit -m "Initial commit with two task files"

### 🔁 Making Changes
echo "This is Task 3 content" >> task3.txt
git status
git add task3.txt
git commit -m "Updated task3.txt with content"

### 🧾 Logs and Show
git log
git show 5ead610

### 🚀 Push to GitHub
git push origin main

### 🔁 Pull Remote Changes
git pull
