# How does Git&Github work? 

### 1. Download files stored on Github 
```
git clone <url>
```
#### - If you already have files stored, you don't need to download the files again. 
#### - vs. **Downloading the zip file:** You download the Git file with the history of commits while with the zip file, you only have that version. 
#### - vs. **git pull:** You download the contents of the files while git pull only brings the commit history. 

### 2. Make amendments to the file locally 
```
git add <file>
git commit -m 'message'
...
```

### 3. Update your local files to Github 
```
git push origin main
```
#### - origin stands for the name of the repository on Github
#### - main stands for the name of the branch 

### 4. If you need to update to the newest version updated onto Github by your colleagues... 
```
git pull origin main 
```
#### - origin stands for the name of the repository on Github
#### - main stands for the name of the branch 

### 5. Other useful tips & tricks
```
git remote add origin <url>
```
#### - To create a repository by code... 
#### - origin stands for the name of the repository on Github
#### - <url> stands for the link to that repository
```
git remote rm origin
```
#### - When you want to remove the repository by code...
```
.gitignore
```
#### - Create a .gitignore file to store any files that you don't want to be tracked by Git. Note: .gitignore is not a code but the name of the file. You have to create the file manually. 

