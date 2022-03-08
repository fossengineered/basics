
# Coding C++

### Turn “Human Readable” code → assembler → machine code

- Compiler installation
    - [https://www.msys2.org/](https://www.msys2.org/)
- add PATH
    
    ```bash
    hold windows key + r (opens the run window)
    sysdm.cpl
    ```
    
    - click advanced tab
    - click Environment Variables
    - click the PATH entry
    - click EDIT
    - click new and paste in the path
        
        ```bash
        C:\msys64\mingw64\bin
        ```
        
    
    - click ok on all the open windows
    - open the CMD window then run the following command

```bash
g++ --version
```

### Create application code in Notepad

- Open Documents Folder
    - create subfolders

```bash
CodeProjects->HelloWorld
```

- Shell use
    - open CMD from windows key+r
    - navigate to <copy link from explorer window>
    
    ```bash
    cd %userprofile%\documents\CodeProjects\HelloWorld
    echo nul > main.c
    ```
    
### Compile application

- open CMD from windows key+r
    - navigate to <copy link from explorer window>
    
    ```bash
    cd %userprofile%\documents\CodeProjects\HelloWorld
    ```
    
- Run

```bash
g++ main.c -o main.exe
```
