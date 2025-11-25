Linux Commands / Cheatsheet

Basic Navigation

`pwd` = Show current directory
`ls` = List files and directories
`ls -l` = Long listing format
`ls -a` = Show hidden files
`cd dirname` = Change directory
`cd ..` = Move up one directory
`cd /` = Go to root
`cd ~` = Go to home
`clear` = Clear terminal
`history` = Show command history

File & Directory Management

`touch file` = Create an empty file
`mkdir dir` = Create directory
`rmdir dir` = Remove empty directory
`rm file` = Remove file
`rm -r dir` = Remove directory recursively
`cp src dest` = Copy file
`cp -r src dest` = Copy directory
`mv src dest` = Move or rename
`cat file` = View file content
`less file` = Paginated view
`head file` = First 10 lines
`tail file` = Last 10 lines
`tail -f file` = Live file output

Permissions & Ownership

`chmod 755 file` = Change permissions
`chmod u+x file` = Make executable
`chown user:group file` = Change owner
`ls -l` = View permissions

System Info

`uname -a` = Full system info
`hostname` = Show system hostname
`uptime` = System uptime
`top` = Running processes
`htop` = Interactive process viewer
`df -h` = Disk space usage
`du -sh *` = Directory sizes
`free -h` = Memory usage
`lscpu` = CPU info
`lsblk` = Block devices

Process Management

`ps` = Show processes
`ps aux` = Detailed process list
`kill PID` = Kill process
`killall name` = Kill by name
`bg` = Resume in background
`fg` = Bring to foreground
`jobs` = List jobs

Networking

`ifconfig` = Network info
`ip a` = Show IP addresses
`ping host` = Test connection
`ss -tuln` = Show open ports
`curl url` = Get data from URL
`wget url` = Download file
`ssh user@host` = Remote login
`scp file user@host:/path` = Secure copy

Package Management (Ubuntu/Debian)

`sudo apt update` = Refresh packages
`sudo apt upgrade` = Upgrade all
`sudo apt install pkg` = Install package
`sudo apt remove pkg` = Remove package
`sudo apt autoremove` = Clean leftovers

Package Management (RHEL/CentOS)

`sudo yum update`
`sudo yum install pkg`
`sudo yum remove pkg`
`sudo dnf install pkg`

Archiving & Compression

`tar -cvf file.tar dir` = Create tar
`tar -xvf file.tar` = Extract tar
`gzip file` = Compress
`gunzip file.gz` = Decompress
`zip http://file.zip files` = Zip
`unzip http://file.zip` = Unzip

User Management

`whoami` = Current user
`who` = Logged-in users
`id` = User info
`sudo adduser user` = Add user
`sudo passwd user` = Change password
`sudo deluser user` = Remove user
`su user` = Switch user
`logout` = Exit session

Shutdown & Reboot

`sudo shutdown now` = Shutdown
`sudo shutdown -r now` = Reboot
`reboot` = Restart
`poweroff` = Power off

Searching

`find /path -name file` = Search by name
`grep 'text' file` = Search inside file
`grep -r 'text' dir` = Recursive search
`locate file` = Fast search
`updatedb` = Update locate database

Disks & Filesystems

`fdisk -l` = List partitions
`mkfs.ext4 /dev/sdX` = Format disk
`mount /dev/sdX /mnt` = Mount
`umount /mnt` = Unmount

Environment & Variables

`echo $PATH` = Show PATH
`export VAR=value` = Set variable
`env` = Show all variables

Useful Commands

`man cmd` = Manual pages
`alias ll='ls -la'` = Create shortcut
`date` = Show date/time
`cal` = Show calendar
`exit` = Close terminal