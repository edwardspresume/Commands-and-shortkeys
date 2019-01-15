# Terminal Commands

### Files and directory
| Command           | Description          |
| ----------------- | -------------------- |
| `nano--gedit--vi` | Open the text editor |



### Directories
| Command                                                                         | Description                                                                          |
| ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| `pwd`                                                                           | Displays  current working directory                                                  |
| `ls`                                                                            | List files in a directory                                                            |
| `ls -l`                                                                         | List files in a detailed format                                                      |
| `ls -f`                                                                         | Show full list of files including hidden                                             |
| `ls -al`                                                                        | Show full list of files including hidden in a detailed format                        |
| `cd [directory name]`                                                           | Change into the specified directory                                                  |
| `mkdir [directory name]`                                                        | Create a directory if it does not already exist                                      |
| `mkdir -p [directory name]`                                                     | The -p flag allows us to create more then one directory                              |
| `cd !$`                                                                         | cd into last mkdir path                                                              |
| `cp -r [original directory name] [new directory name or directory destination ` | Copy a directory recursively give it a new name or place it in a specified directory |
| `rmdir [directory name]`                                                        | remove an empty directory                                                            |



### File operations
| Command                                                            | Description                                                             |
| ------------------------------------------------------------------ | ----------------------------------------------------------------------- |
| `touch`                                                            | creates a new file                                                      |
| `touch -d [timestamp] [file name]`                                 | The -d flags allows us to update the timestamp of a file                |
| `rm`                                                               | Removes a file                                                          |
| `cp [original file name] [new file name or directory destination ` | Copy a file and give it a new name or place it in a specified directory |
| `cat [file name]`                                                  | output the contents of a file                                           |
| `vim [file name]`                                                  | Opens a file to then edit with more capabilities                        |
| `nano--gedit--vi [file name]`                                      | Open the text editor                                                    |



| Command                    | Description                         |
| -------------------------- | ----------------------------------- |
| `sudo reboot`              | Restart laptop/desktop              |
| `[command] !!`             | Run last command as sudo/root       |
| `which [application name]` | Tell where a app is in the system   |
| `reset`                    | Restore a console to a normal state |



- **mv** : moves (or renames) a file/directory

## Text editor

- **vi** : opens up text editor
- **i** : allows the user to insert text
- **`esc` :wq** : save and exit the text editor

## Network

- **ping** : Test a network connection

## Short keys

- **crl+r** : History of past commands
- **crl+a**: Jump to the front of current line
- **crl+e**: Jump to the end of current line
- **ctrl+l/clear** : Clears the screen
