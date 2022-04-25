
# Linux Commands
![Commands](https://i.imgur.com/kAVz68W.jpg)

## Disclaimer
```javascript
[] = optional
{} = requiered

*The most of the time you can write a command with --help or -h, and it will display all the available options*
```

|Commands|Description|Syntax|
|--------|-----------|-------|
|`man`|Shows the manual of a command|`man [command]`|
|`ps`|Show processes|`ps [options] [conditions]`|
|`top`|Dynamic real-time proccesses view|`top [options]`|
|`htop`|Show processes|`htop [options]`|
|`pstree`|Show processes|`pstree [options] [pid or username]`|
|`sudo`|Execute as super user|`sudo {parameter}`|
|`su`|Execute as super user|`su [option] [-] [user]`|
|`whoiam`|Return username of actual user|`whoiam [options]`|
|`more`|View files in the command prompt|`more [option] {file}`|
|`tail`|Print the last 10 lines of each file specified|`tail {parameter} {file}s`|
|`head`|Print the first 10 lines of each file specified|`head {parameter} {file}s`|
|`cp`|Copy files from a source to a destination|`cp [option] {source} {destination}`|
|`alias`|Shortcut that reference a command|`alias [option] {name}='{value}'`|
|`mv`|Move files from a source to a destination|`mv [option] {source} {destination}`|
|`rm`|Delete a specified file or files|`rm [option] {file}`|
|`rmdir`|Delete a specified directory or directories|`rmdir [options] {directory}`|
|`useradd`|Create a new user|`useradd [option] {username}`|
|`passwd`|Change the password of a user|`passwd [option] {username}`|
|`less`|The opossite of more|`less [option] {file}`|
|`history`|Prints a list of commands used in the terminal|`history [option]`|
|`apt`|Command line interface|`apt {parameter} {package}`|
|`ls`|List information about the files and directories|`ls [option] [file/directory]`|
|`mkdir`|Create a directory|`mkdir [option] {drectory}`|
|`ip`|Display network information|`ip [option] {parameter}`|
|`du`|Size of a file|`du [options] {file}`|
|`stat`|Show creation date and last access|`stat [option] {file}`|
|`chown`|Change file or directory owner|`chown [option] {owner}:[group] {file/directory}`|
|`chmod`|Change file o directory permissions|`chmod {parameter} {owner}:[group] {file/directory}`|
|`df`|Report file system disk space usage|`df [option] [file]`|
|`mount`|Mount devices on file system|`Mount [option] [type] {device} {dir}`|
|`gparted`|Gnome Partition Editor|`{device}`|
|`kill`|Kill a process|`kill [option] {pid}`|
|`pwd`|Shows actual directory|`pwd [options]`|
|`echo`|Print text|`echo [option] {text}`|
|`cat`|Prints the content of a file|`cat [option] {file}`|
|`cd`|Helps to move between directorys|`cd [options] {directory}`|
|`wget`|Download files from the internet|`wget [option] {URL}`|
|`pacman`|Packange manager of Arch-Linux Distros|`pacman {parameter} {package}s`|
|`touch`|Create a new file|`touch [option] {filename}`|
|`tree`|List contents of directories in a tree-like format|`tree [option] [directory]`|
|`grep`|Print lines that match the parameter|`grep [option] {parameter}s`|
|`nano`|Terminal text editor|`nano [option] {filename}`|
|`vim`|Another text editor|`vim [option] {filename}`|
|`crontab`|Open the crontab file|`crontab {parameter} [user] [file]`|
|`ln`|Create a hard link|`ln [option] {target} {directory}`|
|`ln`|Create a hard link|`ln -s {target} {directory}`|
|`mdadm`|Raid creator tool|`mdad [mode] <raiddevice> [options] <component-devices>`|
|`chsh`|Change bash|`chsh [option] {parameter}`|
|`bash`|Execute a bash|`bash [option] {bash-file}`|

## Docker commands
```javascript
docker pull    #Download a Docker image
docker build   #Build an image from a Dockerfile
docker images  #List all images on a Docker host
docker run     #Run an image
docker ps      #List all runing and stopped instances
docker stop    #Stop a running instance
docker rm      #Remove an instance
docker rmi     #Remove an image
```

![Commands](https://www.omgubuntu.co.uk/wp-content/uploads/2016/10/GOUKlfP.jpg)
