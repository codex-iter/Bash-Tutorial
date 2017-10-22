# Bash-Tutorial
A cheat sheet for bash


## Simple traversal 


`pwd` : prints working directory

`ls` : lists contents of current directory

`ls -l` : list contents of current directory with extra details

`ls -a` : list hidden files too

`ls /home/user/*.txt` : lists all files ending with `.txt` inside `/home/user`


`cd` or `cd ~` : change directory to your home directory

`cd folder1/folder2/` : change directory to `folder2` inside `folder1`


`mkdir mydir` : create a new directory named `mydir`

`rmdir mydir` : remove directory `mydir`


`touch myfile` : create or update a `myfile`


`cp myfile myfile2` : copy `myfile` into `myfile2`

`cp -r mydir mydir2` : copy `mydir` into `mydir2` (creates new directory if it doesn't exist)


`rm myfile` : removes `myfile`

`rm -rf mydir` : removes `mydir` and all its contents


`mv myfile mydir/` : moves `myfile` into `mydir`

`mv myfile newfile` : renames `myfile` to `newfile`

`mv mydir newdir` : renames `mydir` to `newdir`


`cat file` : outputs the contents of `file`

`cat > file` : places standard input into `file` (`^c` to end)

`head file` : output first 10 lines of `file`

`tail file` : output last 10 lines of `file`

`tail -f file` : output contents of `file` as it grows (`^c` to exit)


`nano` : opens a terminal editor

`nano newfile` : opens newfile for editing


`echo text` : prints text on the screen

`echo text >> newfile` : creates `newfile` with text


## Process Management

`ps` : Display your currently active processes

`top` : display all running processes

`htop` : more interactive and colorful version of `top`

`kill pid` : kill process with id `pid`

`killall proc` : kill all processes named `proc*`


## System info

`date` : show the current date and time

`cal` : show this month's calendar

`uptime` : show current uptime

`uname -a` : show all kernel information

`cat /proc/cpuinfo` : show cpu information

`cat /proc/meminfo` : show memory information

`df` : show disk usage

`du` : show directory space usage

`free` : show memory and swap usage

`whereis app` : show possible location of app

`which app` : show which app will be run by default


## Help

`man command` : shows manual for `command`

`command --help` or `command -h` : (almost always) shows short help about the command


## Network

`ping host` : ping host and output results

`whois domain` : get whois information for domain

`dig domain` : get DNS information for domain

`dig -x host` : reverse lookup host

`wget file` : download file

`wget -c file` : continue a stopped download


## Installation

### Install from repository

#### Ubuntu/Debian based systems

`sudo apt-get update` : updates repository list

`sudo apt-get upgrade` : installs possible updates

`sudo apt-get install package` : installs package

`aptitude search package` : searches for the package

#### Fedora

`yum update` : updates repository list

`yum search package` : searches for package

`sudo yum install package` : installs package


## Install from file

`sudo dpkg -i package.deb` : install package from deb file (Debian)

`sudo rpm -Uvh package.rm` : install package from rpm file (Fedora)

## Install from source

`./configure`

`make`

`make install` 

May require `sudo`. Read the README for the source before proceeding.
