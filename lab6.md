# Git Commands
# Lab6_Lecture note

#### $ git init
Initializing a Repository in an existing directory
```sh
$ git init
Initialized empty Git repository in C:/Users/Teddy/Desktop/2023_2/OSS/.git/
```

#### $ git status
Checking Repository Status
```sh
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ExampleFile.txt

nothing added to commit but untracked files present (use "git add" to track)
```

#### *about status*
```sh
Changes to be committed:  
  (use "git rm --cached <file>..." to unstage)  

Changes not staged for commit:  
  (use "git add <file>..." to update what will be committed)  
  (use "git restore <file>..." to discard changes in working directory)  

Untracked files:  
  (use "git add <file>..." to include in what will be committed)  
```
**VARIFY that the file will be committed**  


#### $ git add [file_name]
Adding a new file to be staged (tracked)
```sh
$ git add README.md
```



#### $ git add .
Adding all files to be staged (tracked)

#### $ git rm --cached [file_name]
Unstaging a file

#### $ nano .gitignore
Ignore the file by creating a .gitignore file and writing the file name on it.


- *\*.a*   
*ignore all .a files*
- *!lib.a*  
*but do track lib.a, even thouh you're ignoring .a files above*  
- */TODO*  
*only ignore the TODO file in the current directory, not subdir/TODO*  
- *build/*   
*ignore all files in any directory named build*  
- *doc/\*.txt*  
*ignore doc/note.txt, but not doc/server/arch.txt*  
- *doc/\*\*/\*.pdf*  
*ignore all.pdf files in the doc/ directory and any of its subdirectories*  

#### git commit
Commit

#### git commit -m "[commit message]"
Add -m is recommended.

#### git log
Check log

#### git branch -m [branch_name] [new_branch_name]
Change branch name
