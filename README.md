# Data Tools Project - Setting Up Version Control for a Personal
By Matișan Rareș-Ștefan

## Tasks 
### Github account creation
I have created the Github account as instructed on their website.

### Initialize a Local Git Repository
I have set up the local Git repository using the following command in bash:
```bash```
git init

### Add Files and make Initial Commit
Further, I've created the necessary files for my application directly in my IDE, where the repository is. Next, in order to add the files to the staging are, I used the following bash command:
```bash```
git add .

Also, I used this bash command to make my first initial commit:
```bash```
git commit -m "Initial commit"

### Create and Connect Remote Repository
Firstly, I created the new repository in Github.
I've already created a remote repository for the origin beforehand in another repository than the one specified, so I used this command in order to change to 'market-prediction':

```bash```
git remote set-url origin https://github.com/raresmatisan/market-prediction.git

### Push to Github
I have used the incorporated Git section in PyCharm to do the second commit after and the I pushed everything to the origin.
![commit_push](https://github.com/user-attachments/assets/a087b893-3d3d-4236-bf9f-17560db27d8d)

### Create and Switch branches. Commit Changes
Next up, I've created the new branch following the instruction from this bash command:

```bash```
git checkout -b feature/add-about-project

Now that I am working in this branch, I will create the text file 'appinfo.txt', where I will add the details about the application. I've added the new text file to the staging area by using this bash command:

```bash```
git add appinfo.txt

And finally, I've commited everything with this bash command:

```bash```
git commit -m "Added appinfo.txt with the application's explanation"

### Pull Changes from the Main Branch
I switched back to the Main Branch (called in my case origin/master) using this bash command:

```bash```
git checkout master

As a change, I added a comment in my 'main.py' file. I switched back to the other branch, using the same command from above. In order to pull from the Main Branch, I used this command:

```bash```
git pull origin master

Finally, I pushed and committed all the changes, using the IDE, as visualized in Figure \ref{fig:commit_push}.
