# Lecture Note_About Shell Commands


### **Shell Commands** 

#### **pwd**
shows the current path in a hierarchical directory   

```sh
$ pwd
/c/Users/UserName
```

#### **cd**
change directory

#### **ls**
list files and directories

```sh
$ cd Desktop
$ ls
 file_1/   file_2/
```

More in ls (example)
- ls /bin
- ls -l
- ls -l /etc/bin
- ls -la .\.

Refer to the explanation [here](https://linuxcommand.org/lc3_lts0050.php)

#### **clear**
clear Shell terminal

```sh
$ ls
README.md
$ clear
```
```sh
$
```

### **Manipulation**
*Warning: These commands may delete or overwrite your files and directories*
***Make sure to backup your important contents***

#### **cp**
copy files and directories

```sh
$ ls
README.md
$ cp README.md  backup_README.md
$ ls
README.md  backup_README.md
```

#### **mv**
move files and directories or rename them

```sh
$ ls
README.md
$ mv README.md  new_README.md
$ ls
new_README.md
```

#### **rm**
delete files and directories ***permantely and irreversevely***

```sh
$ ls
README.md  backup_README.md
$ rm README.md
$ ls
backup_README.md
```

#### **mkdir**
make a new directory

```sh
$ ls 
directory1  directory2
$ mkdir new_directory
$ ls
directory1  directory2  new_directory
```

#### **Wildcards**
example: 

pattern
- \* 
- g*  
- b*.txt
- Data???

command
- cp *.txt text_files
- mv dir1 .\./*.bak dir2
- rm *~

Refer to the explanation [here](https://linuxcommand.org/lc3_lts0050.php)

#### **exit**
exiting terminal
```sh
$ exit
```


---

More info: [Linux Command](https://linuxcommand.org/)
