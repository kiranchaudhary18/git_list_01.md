#### Task 2: Initialize a Repository

1.First of all creat a new folder and navigate to folder

   mkdir new_folder
   cd new_folder

2.intialize a git repository

   git init

#### Task 3: Create a File and Make Multiple Commits

1.first creat a new file using echo

   echo "my new_file" >new_file

2.add a file in stagging area

   git add .

3.commit the file

   git commit -m "first commit"

4.update a file using echo

   echo " updated new_file" >new_file

5.add a file stagging area 

   git add .

6.commit the file

   git commit -m "second commit"

7.push the file in github

   git push


####  Task 4: Check Status and Log 

1.git status check the file is add or not in repository

   git status

2.git log check the commit history

   got log


#### Task 5: Create and Clone a Repository

1.first creat  repository on your github

2. copy the url any other repository and git clone 

   git clone https://github.com/VasaraSujal/Porter.git


#### Task 6: Understanding the Git Workflow

1.first cerat a file 

   echo "workflow" >workflow.md

2.add the file

   git add .

3.commit the file

   git commit -m "added"

   
#### Part 2: Working with Repositories

#### Task 7: Branching and Merging

1.first creat a branch and checkout with feature

   git branch feature
   git checkout feature

2.creat a new file

   echo "file" >login

3.add the file and commit

   git add .
   git commit -m "hi"

4.checkout branch main and merge with feature

   git checkout main
   git merge feature 


#### Task 8: Handling Merge Conflicts

1.first creat a two branch

    git branch branch-A
    git branch branch-B

2.merge barnch-A into main

   git checkout main
   git merge barnch-A    

3.merge barnch-B into main

   git checkout main
   git merge barnch-B

4.add a file and commit 

  git add .
  git commit -m "hi"    

#### Task 9: Renaming and Deleting Branches

1.first creat a file 
  
  echo "test" > test5

2.add the file and commit 
  
  git add.
  git commit -m "hi"

3.rename a branch 
  
  git branch main featuer

4.delete a featuer branch
  
  git checkout main
  git branch -d featuer
   
   
#### Part 3: Advanced Git Operations   

#### Task 10: Using Git Stash

1.first creat a file

    echo "new" >test6.md

2.git stash is save the working direcu,con 