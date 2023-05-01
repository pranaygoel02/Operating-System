# Operating System (Linux commands)

- ### pwd (Present Working Directory)
Outputs the path to present working directory 
```
pwd
```
- ### mkdir (Make Directory)
```
mkdir <directory-name>
```
- ### rmdir (Remove Directory)
```
rmdir <directory-name>
```
- ### ls (List)
Used to list contents inside a directory.
```
ls
```
To display all hidden files as well, use `-a` -> (all)
```
ls -a
```
To see more info about all listed files, use `-l`
```
ls -l
```
To see all files in sub-directories, use `-R` -> (Recursive)
```
ls -R
```
- ### cd (Change Directory)
Used to change working directory. Press `TAB` to autocomplete.
```
cd <directory-path>
cd users/public/Folder/test.txt
```
Use `..` to go back by one step. Chain it to go multiple back.
```
cd ..
cd ../../
```
- ### touch
Used to create empty files. We can create multiple empty files by executing it once.
```
touch <file name>  
touch <file1>  <file2> ....
touch test1.txt tes2.txt
```
- ### cat
The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.
    - Create a file. Press `CTTRL + D` to save and exit input operation.
  ```
  cat > <file-name>
  // Enter file content
  ```
    - To display the content
  ```
  cat <file-name>
  ```
    - It can also be used to merge contents of some file into one file.
    ```
    cat <file-1> <file-2> > <file-3>
    ```
    `>` is called funnel.
- ### tac
Same as `cat`. Prints content from last to first
- ### rm (Remove)
 Used to remove a file
 ```
 rm <file-name>
 ```
- ### cp (Copy)
 Used to copy a file or directpry
  - Copy in same directory.
  ```
  cp <existing-file-name> <new-file-name>
  ```
  This will create a new file if the destination file does not exists. 
  - Copy in different directory
  ```
  cp <existing-file-name> <destination-directory>
  ```
- ### mv (Move)
    - Used to move a file or directory from one location to another.
    - Replace `cp` with `mv`.
    - Similar to `cut`.
- ### head
Used to display the first 10 lines in a file.
```
head <file-name>
```
- ### tail
Used to display  the last 10 lines in a file
```
tail <file-name>
```
- ### su
The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.
```
su <user-name>
```
- ### 
