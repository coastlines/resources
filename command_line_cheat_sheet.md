# General Commands

### VERSION CONTROL (GIT) COMMIT CHEATSHEAT

| Key/Command             | Description                                                 |
| ----------------------- | ----------------------------------------------------------- |
| git pull                | Retrieves the latest changes from the remote repository and merges them into the current branch. |
| git checkout -b my-new-branch | Creates a new branch named "my-new-branch" and switches to it. Drop the "-b" to switch to an existing branch |
| git status              | Displays the current state of the repository, including modified files, untracked files, and branch information. |
| _Make the changes and hit save_ | _Modify the necessary files and save the changes._ |
| _Add all files or one file_ | _Use **ONE** of the following git add commands._ |
| git add 'filename'      | Add specific file                                           |
| git add .               | Adds all the modified files to the staging area in preparation for committing them. |
| git commit -m "My new changes" | Commits the changes with a descriptive message explaining the modifications made. |
| git push origin my-new-branch | Pushes the committed changes to the remote repository, specifically to the "my-new-branch" branch. |
| _Repeat!_| Each time you add a commit you are creating a version of the code that you can revert to or review. Commiting and testing often can help you catch and isolate changes that cause errors.|


### SHORTCUTS

| Key/Command             | Description                                                 |
| ----------------------- | ----------------------------------------------------------- |
| Tab                     | Auto-complete files and folder names                        |
| Ctrl + A                | Go to the beginning of the line you are currently typing on |
| Ctrl + E                | Go to the end of the line you are currently typing on       |
| Ctrl + U                | Clear the line before the cursor                            |
| Ctrl + K                | Clear the line after the cursor                             |
| Ctrl + W                | Delete the word before the cursor                           |
| Ctrl + T                | Swap the last two characters before the cursor              |
| Esc + T                 | Swap the last two words before the cursor                   |
| Ctrl + R                | Lets you search through previously used commands            |
| Ctrl + L or Command + K | Clears the Screen                                           |
| Ctrl + C                | Kill whatever you are running                               |
| Ctrl + D                | Exit the current shell                                      |

### GIT COMMANDS

| Key/Command             | Description                                                 |
| ----------------------- | ----------------------------------------------------------- |
| git clone               | Clone a repository                                          |
| git status              | Check status of recently edited files                       |
| git add 'filename'      | Add specific file                                           |
| git add .               | Add all files                                               |
| git commit -m 'message' | Commit your changes before pushing to github                |
| git push                | Push changes to github                                      |
| git checkout -b 'branch name' | Create a new branch                                   |
| git checkout 'branch name'  | Switch to another branch                                |


### CORE COMMANDS

| Key/Command      | Description                                                               |
| ---------------- | ------------------------------------------------------------------------- |
| cd               | Home directory                                                            |
| cd \[folder\]    | Change directory                                                          |
| cd \~            | Home directory, e.g. ‘cd \~/folder/’                                      |
| cd /             | Root of drive                                                             |
| ls               | Short listing                                                             |
| ls -l            | Long listing                                                              |
| sudo \[command\] | Run command with the security privileges of the superuser (Super User DO) |
| open \[file\]    | Opens a file                                                              |
| open .           | Opens the directory                                                       |
| q                | Exit                                                                      |
| clear            | Clear screen                                                              |

### COMMAND HISTORY

| Key/Command | Description                                                    |
| ----------- | -------------------------------------------------------------- |
| history n   | Shows the stuff typed - add a number to limit the last n items |
| ctrl-r      | Interactively search through previously typed commands         |
| \!\[value\] | Execute the last command typed that starts with ‘value’        |
| \!\!        | Execute the last command typed                                 |

### FILE MANAGEMENT

| Key/Command                  | Description                              |
| ---------------------------- | ---------------------------------------- |
| touch \[file\]               | Create new file                          |
| pwd                          | Full path to working directory           |
| ..                           | Parent/enclosing directory, e.g.         |
| cd ../../                    | Move 2 levels up                         |
| .                            | Current folder                           |
| echo                         | Show the value of an environment variable|
| cat                          | Concatenate to screen (show content)     |
| rm \[file\]                  | Remove a file, e.g. rm \[file\] \[file\] |
| rm -i \[file\]               | Remove with confirmation                 |
| rm -r \[dir\]                | Remove a directory and contents          |
| rm -f \[file\]               | Force removal without confirmation       |
| rm -i \[file\]               | Will display prompt before               |
| cp \[file\] \[newfile\]      | Copy file to file                        |
| cp \[file\] \[dir\]          | Copy file to directory                   |
| mv \[file\] \[new filename\] | Move/Rename, e.g. mv -v \[file\] \[dir\] |

### DIRECTORY MANAGEMENT

|  Key/Command             | Description                                             |
| ------------------------ | ------------------------------------------------------- |
| mkdir \[dir name\]       | Create new directory                                    |
| mkdir -p \[dir\]/\[dir\] | Create nested directories                               |
| rmdir \[dir\]            | Remove directory ( only operates on empty directories ) |
| rm -R \[dir\]            | Remove directory and contents                           |
| pwd                      | Full path to working directory                          |

### VIM
##### Note: The commands after `vim` only work once you have opened a file with vim

|  Key/Command             | Description                                             |
| ------------------------ | ------------------------------------------------------- |
| vim                      | Open a file with vim                                    |
| i                        | Insert or edit text                                     |
| `esc` button             | Exit insert mode                                        |
| :w                       | Write changes                                           |
| :q                       | Quit vim                                                |
| :wq                      | Write changes & quit vim                                |

### FURTHER READING
* [Launch School CL Introduction](https://launchschool.com/books/command_line/read/introduction)
* [Learn Enough CLI Tutorial](https://www.learnenough.com/command-line-tutorial/basics)
* [Programming Historian Intro to Bash](https://programminghistorian.org/en/lessons/intro-to-bash)
* [VIM Cheat Sheet](https://vim.rtorr.com/)
