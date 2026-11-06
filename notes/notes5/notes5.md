# Notes 5 

## Command Definitions 

1. ls command
   **Definition**
    * The ls command shows the list of files and folders in the working directory. 
      **Usage/Formula**
        ```ls [optionflag] [directoryname]```
    **Example**
        ```ls -a Downloads/``` --Shows hidden files 
2. pwd command 
    **Definition**
     * The pwd command shows the path of the current working directory the user is working in 
    **Usage/Formula** 
     ```pwd``` --displays current location
    **Example Output**
        ```/home/d13/Downloads/lab5files```
3. cd command 
    **Definition**
    * The cd command stands for "Change Directory" and allows the user to migrate from one folder to another
    **Usage/Formula** 
        ```cd[directory name]```
    **Example**
        ```cd Documents``` --move into a folder 
        ```cd ..``` --move back one folder 

## Answers to Part II Questions

1. A variable is a name that stores information to be used at a different point. 
2. To use a variable, one must be created by giving it a name, followed by an equal sign, then the value it will hold. To display what is inside of the variable, we must use the echo command and dollar sign before variable name. 
    **Example** ```name = "Taylor"``` ```echo $name```
3. An environment variable is a variable is stored by the computer's OS to gain information about the system   
    **Example** ```echo $USER``` -- displays current desktop username
4. A user-defined variable is a variable created by the user
    **Example** ```name = "Taylor"``` 
5. The root directory is the starting point for all files and folders within a LInux system represented by a forward slash (/)
6. A Parent Directory is a folder that contains another folder.
7. Current Working Directory means the folder the user is currently working in and can be accessed using the pwd command 
8. An absolute path is the full location layout of a file or folder, always beginning at the root. 
     **Example** ```/home/d13/Downloads/lab5files``` 
9. A relative path is the location of a file or folder based on wherever the user is working and does not begin at the root. 
        **Example** ```/Downloads/lab5files``` 
10. "Your home directory" is the user's personal folder in Linux that stores files, documents, and other personal info while "The home directory" is the general location where all users folders are stored. 