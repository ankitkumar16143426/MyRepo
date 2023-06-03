ANKIT KUMAR   
Initialize an empty git repository.
Ans  : git init

Create a file named first.txt.
Ans : touch first.txt

Add first.txt to the staging area.
Ans  :    git add first.txt

Commit with the message "adding first.txt".
Ans  :    cd my-repo
             git add first.txt
             git commit -m "adding first.txt"
             
Check out your commit with git log.
Ans  :  git log
           commit 1234567890abcdef1234567890abcdef12345678
           Author: Ankit Kumar <ankitkumar16143426@gmail.com.com>
           Date:   Sat Jun 1 00:00:00 2023 +0100
           Updated README.md
           git checkout 1234567890abcdef1234567890abcdef12345678
           
Create another file called second.txt.
Ans :  touch second.txt

Add second.txt to the staging area.
 Ans : git add second.txt
 
Commit with the message "adding second.txt"
Ans : git add second.txt
       git commit -m "adding second.txt"
       
Remove the first.txt file
Ans : git rm first.txt

Add this change to the staging area
Ans : git add <file1> <file2> ...
         git add example.txt
         git add .
  
Commit with the message "removing first.txt"
Ans : git commit -m "removing first.txt"
  
Check out your commits using git log
Ans : git log
         git checkout <commit-hash>
  
Create a github repository with your own name
Ans : MyRepo

