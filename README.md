# Creating github repo from cli

- git init
- git add README.md
- git commit -m "first commit"
- git branch -M main
- git remote add origin https://github.com/DL-Murali/murali-git.git
- git push -u origin main

## Steps

- Open Git Bash terminal and create one project directory
- write your code files in created project directory
- **Make that directory as git repository**
  - git init <! -- this will initialize this directory as git repository -->

- **Configure your github details first**
  - git config --global user.name "your github username"
  - git config --global user.email "your github email"
  - git config --global color.ui true


- **Now add your changes to Staging area**
  - git add .  <! -- this will add all changes to staging area -- >

- **Now commit your changes from Staging area to Local repository**
  - git commit -m "your-message"    <! -- Commits your changes to Local Repo -->

- Now goto your Github and create one Repo with Project Directory name
- copy the repo url

- Now Goto your Git Bash terminal
- **Add your Remote Repo url to Project Directory**
  - git remote add origin https://github.com/DL-Murali/murali-git.git     <! -- This will attach your remote repo to Project directory -->

- **Set your branch name**
  - git branch -M main

- **Now push your changes to Github Remote repository**
  - git push -u origin main
- 
