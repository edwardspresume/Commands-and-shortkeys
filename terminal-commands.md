# Terminal short-keys and Commands

grep -Ril "text-to-find-here" /
&nbsp;

### Package manager

| Description                                                             | Command                     |
| ----------------------------------------------------------------------- | --------------------------- |
| Update package in system                                                | `sudo pacman -Syu`          |
| Install a package                                                       | `sudo -s [package name]`    |
| Remove package                                                          | `sudo -R [package name]`    |
| Download dependency                                                     | `sudo apt -f install`       |
| Update for node packages                                                | `sudo pacman --force -Syyu` |
| list all packages explicitly installed and not required as dependencies | `pacman -Qet`               |

&nbsp;

### Short-keys

| Description                       | Command           |
| --------------------------------- | ----------------- |
| History of past commands          | `crl+r`           |
| Jump to the front of current line | `crl+a`           |
| Jump to the end of current line   | `crl+e`           |
| Clear the terminal                | `ctrl+l or clear` |
| Open an editor to run a command   | `ctrl+x+e`        |

&nbsp;

### File operations

| Description                                                             | Command                                                           |
| ----------------------------------------------------------------------- | ----------------------------------------------------------------- |
| Creates a new file                                                      | `touch [file name]`                                               |
| The -d flags allows us to update the timestamp of a file                | `touch -d [timestamp] [file name]`                                |
| Removes a file                                                          | `rm [file name]`                                                  |
| Remove all the files of the current directory                           | `sudo rm -f *`                                                    |
| Remove all the files with that extension                                | `sudo rm *[.ext]`                                                 |
| Remove all the nested files with that extension                         | `find -maxdepth 2 -mindepth 1 -type f -name "*.png" -delete`      |
| Copy a file and give it a new name or place it in a specified directory | `cp [original file name] [new file name or directory destination` |
| Output the contents of a file                                           | `cat [file name]`                                                 |
| Output the contents of a file in chucks                                 | `less [file name]`                                                |
| Opens a file to then edit with more capabilities                        | `vim [file name]`                                                 |
| Open the text editor                                                    | `nano/gedit/vi [file name]`                                       |

&nbsp;

### Directories

| Description                                                                          | Command                                                                        |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| Go to root folder                                                                    | `cd /`                                                                         |
| Displays current working directory                                                   | `pwd`                                                                          |
| List files in a directory                                                            | `ls`                                                                           |
| List files in a detailed format                                                      | `ls -l`                                                                        |
| Show full list of files (does that are hidden)                                       | `ls -f`                                                                        |
| Show full list of files in a detailed format                                         | `ls -al`                                                                       |
| do not ignore entries starting with .                                                | `ls -a/--all`                                                                  |
| Change into the specified directory                                                  | `cd [directory name]`                                                          |
| Create a directory if it does not already exist                                      | `mkdir [directory name]`                                                       |
| The -p flag allows us to create more then one directory                              | `mkdir -p [directory name]/{sub1, sub2}/{sub3}`                                |
| The -p flag allows us to create more then one directory                              | `mkdir -p [directory name]/{1..100}/{1..100}`                                  |
| cd into last mkdir path                                                              | `cd !$`                                                                        |
| Copy a directory recursively give it a new name or place it in a specified directory | `cp -r [original directory name] [new directory name or directory destination` |
| Remove an empty directory                                                            | `rmdir [directory name]`                                                       |
| Remove all node folders                                                              | `find . -name "node_modules" -type d -prune -exec rm -rf '{}' '+'`             |
| Remove all node folders                                                              | `find . -path '*/node_modules*' -delete`                                       |
| Move all folders in the current directory to another folder                          | `mv -t [destination] ./*`                                                      |

&nbsp;

### Files & Directories

| Description                          | Command             |
| ------------------------------------ | ------------------- |
| Moves (or renames) a file/directory  | `mv`                |
| Remove file or directory recursively | `rm -rf [dir/file]` |

&nbsp;

### General Commands

| Description                                                 | Command                                                         |
| ----------------------------------------------------------- | --------------------------------------------------------------- |
| send ICMP ECHO_REQUEST to network hosts                     | `ping`                                                          |
| check status of a website                                   | `ping [url] -c 3`                                               |
| Open server                                                 | `py -3 -m http.server`                                          |
| Root                                                        | `sudo su`                                                       |
| Restart system                                              | `sudo reboot`                                                   |
| Shutdow the system in given time                            | `sudo shutdown -h [time:15]`                                    |
| Run last command as sudo/root                               | `[Sudo \| command] !!`                                          |
| Tell where a app is in the system                           | `which [application name]`                                      |
| Restore a console to a normal state                         | `reset`                                                         |
| Terminate an application from excuting                      | `killall [app name]`                                            |
| Shows drivers (usb,hardrive, ect...)                        | `sudo blkid`                                                    |
| shows all the commands of a givin thing                     | `man [app, command name ]`                                      |
| Displays operating systems info                             | `screenfetch`                                                   |
| fix a really long command that you messed up through editor | `fc`                                                            |
| Exit terminal but leave all processes running               | `disown -a && exit`                                             |
| Shows where an application is                               | `whereis [application]`                                         |
| Get and set application settings                            | `gsettings get/set org.blueman.transfer shared-path '/home/me'` |

&nbsp;

## Text editor

- **vi** : opens up text editor
- **i** : allows the user to insert text
- **`esc` :wq** : save and exit the text editor

&nbsp;

# Applications

sudo systemctl --failed

sudo timeset-gui

sudo freshclam :: Updates virus database
sudo clamscan -r -i --bell :: Scan dir recursively and only render infected files

&nbsp;

# Tilix

${appName}: ${sessionName}
gsettings set com.gexperts.Tilix.Settings window-style normal

Search for pattern with exclusion: grep -Ril --exclude-={css,js} searchPattern searchDir

```purgecss --css css/header.css --content _.php _.js includes/**/\*.js includes/**/_.php includes/_.php templates/\*_/_.php --out ../unused_css_result/```

Command history: ```history```

cd into folder and run script: (cd /path/to/your/app && npm start && cd -)
npm test --prefix ~/folder path/

To make this changes permanent, you can put this line to your .bashrc, for example. Execute echo 'alias kt="killall gnome-terminal"' >> ~/.bashrc && source ~/.bash_aliases

To refresh your .bashrc file type the following in terminal,
```. ~/.bashrc``` or  ```source .bashrc```

To add an alias type the following in terminal,it will work until you close your terminal.
```alias kt='killall gnome-panel'```

Show system bit: ```uname -m```