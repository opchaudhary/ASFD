#ASFD
# Git Github Practice

# Description
To practice upon Git Github

## Project Link
- Github: [AFSD](https://github.com/opchaudhary/ASFD)

## Getting Started

1. **Initialize Git :**

   ```bash
   git init
   git status
   ```

2.**Git add in staging area :**

   ```bash
   git add .
   git status
   ``` 

3.**Git Commit :**

   ```bash
    git commit -m "initial commit"
   ``` 

4.**Create new branch :**

   ```bash
   git checkout -b op1
   git branch
   ``` 

5.**Updated  in new branch:**

   ```bash
   git add .
   git commit -m "change in op1"
   ```

6.**Create and resolve merge conflict:**

 - `Create new branch op1`


     ```bash
     git checkout -b op1
     ``` 
 - `Update and commit new change in branch`
     ```bash
     git status
     git add .
     git commit -m "Add op1"
     git stataus
    ```


  - `Merge op1 into main branch`
     ```bash
      git checkout main
      git status
      git merge op1
      git stataus
     ```


  - `Update by op1 branch`
     ```bash
      git checkout op1
      git status
      git add .
      git commit -m "add some line"
      git status
     ```

   - `Merge conflict generated`
     ```bash
      git checkout main
      git merger op1
     ```
   

- `Resolved Merge conflict`
   ```bash
    git add .
    git commit -m "final conflict resolve"
    git status
   ```
   

7.**Create a Github Repository:**

- Github: [AFSD](https://github.com/opchaudhary/ASFD)

- Add url
  
   ```bash
    git remote add origin https://github.com/opchauhdary/git_github_AFSD.git
    git remote -v
   ```


3. **Push project to Github Repository:**

- Github: [AFSD](https://github.com/opchaudhary/ASFD)

-Push master branch

   ```bash
    git push -u origin master
   ```
 

-Push op1 branch

   ```bash
    git push -u origin op1
   ```
 

-Push op2 branch

   ```bash
    git push -u origin op2
   ```
  

## Usage

1. *Learn Git Commands** 



## Author

- OMPRAKASH
