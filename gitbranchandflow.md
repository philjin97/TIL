# Git Branching
### 1. How to Create a Branch
#### a) Create a branch titled 'feature/main'
```
git branch feature/main
```
#### b) Check if the branch you created is actually created
```
git branch
```
#### c) Move to the branch you created
```
git checkout feature/main
``` 
##### Note: if you want to create a branch and move to the newly created branch at the same time, use the code 'git checkout -b feature/main'. 
#### d) After you are finished with your branch, merge the feature/main branch to the main branch.
```
git merge feature/main
```
##### Note: remember to move back to the main branch using 'git checkout main', before merging. 
#### e) Delete the feature/main branch as you don't need it anymore
```
git branch -d feature/main
```
---
### 2. What happens when there is a conflict when merging different branches? 
#### Conflicts happen when the same file is altered in different ways in the different branches. In this case, after you see the conflict, decide how to apply the changes in the specific file, and then add, commit, push again. 
---
### 3. GitHub Flow? - *Shared Repository Model* vs. *Fork & Pull Model*
#### 1. Shared Repository Model 
##### Need an invite to push to the main branch on GitHub. Request Pull. 
#### 2. Fork & Pull Model 
##### Don't need an invite. Fork the main repository to your own repository. After pushing to your own repository, request pull to the original repository. 



