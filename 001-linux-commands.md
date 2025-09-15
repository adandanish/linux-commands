# LINUX COMMANDS

ls - list the files and directories in the current directory
```bash
ls
```

cd - change directory
```bash
cd
```

cd .. - going to previous directory
```bash
cd ..
```

cd / - going to root directory
```bash
cd /
```

cd ~ - going to home(ubuntu)
```bash
cd ~
```

mkdir - create a new directory(folder)
```bash
mkdir dani
```

rmdir - remove directory
```bash
rmdir dani
```

pwd - current path
```bash
pwd
```

cp - copy file or dir
```bash
# We will copy a file called example.txt from the current directory to a directory called backup
cp dani.txt backup/
```

mv - move or rename file/dir
```bash
mv dain.txt dir(name)/
```

rm - remove file/dir
```bash
rm dani.txt
```

touch - create a new empty file or update the timestamp of an existing file
```bash
touch dani.txt
```

cat - concatenate and display files
```bash
cat dani.txt
```

man - manual for a command
```bash
man ls
```

htop - an interactive process viewer and system monitor
```bash
htop
```

chmod - change the permissions of a file or directory
```bash
# The first digit represents the owner of the file/directory
# The second digit represents the group that the file/directory belongs to
# The third digit represents all other users
# 0 (no permission)
# 1 (execute only)
# 2 (write only)
# 3 (write and execute)
# 4 (read only)
# 5 (read and execute)
# 6 (read and write)
# 7 (read, write, and execute)

chmod 700 file.txt
```

chown - change the owner of a file or directory
```bash
chown ammar dani.txt
```

tar - create or extract compressed archive files
```bash
# x: extract files from an archive
# t: list the contents of an archive
# r: append files to an existing archive
# z: use gzip compression
# j: use bzip2 compression
# cf: create file
# xf: extract file
tar cf archive.tar file1 file2 file3
```

gzip - compress files
```bash
gzip file.txt
```

gunzip - decompress compressed files
```bash
gunzip file.txt.gz
```

ssh - connect to a remote server securely
```bash
ssh username@server_address
```

scp - securely copy files between systems
```bash
scp myfile.txt user@remotehost:/home/user/
```

ping - test network connectivity
```bash
ping 8.8.8.8
```

ifconfig - display or configure network interfaces
```bash
ifconfig
```

netstat - display network connection information
```bash
netstat
```

route - view or configure network routing tables
```bash
route [options] [add/delete/show]
```

top - display system resource usage and processes
```bash
top
```

ps - display information about running processes
```bash
ps aux
```

kill - terminate a process
```bash
kill [PID]
```

systemctl - control system services and settings
```bash
# Start the nginx service
systemctl start nginx

# Check the status of the nginx service
systemctl status nginx

# Stop the nginx service
systemctl stop nginx
```

service - control system services
```bash
service - control system services
```

useradd - add a new user to the system
```bash
useradd ammar
```

passwd - change the password for a user
```bash
passwd ammar
```

userdel - delete a user from the system
```bash
userdel ammar
```

su - switch user to become another user
```bash
su tajammal
```

sudo - execute a command as another user or with elevated privileges
```bash
sudo
```

uptime - display system uptime and load average
```bash
uptime
```

df - display disk space usage
```bash
df
```

du - display disk usage by file or directory
```bash
du
```

mount - mount a file system
```bash
sudo mount /dev/sdb1 /mnt/usb
```

umount - unmount a file system
```bash
sudo umount /mnt/usb
```

date - display or set the system date and time
```bash
date
```

whoami - display the current user name
```bash
whoami
```

which - locate a program or command in the system path
```bash
which ls
```

finger - displays all the information about a user
```bash
finger ammar
```

uname - display system information
```bash
uname
uname -a
```

history - display a list of previously executed commands
```bash
history
```

echo - display text or variables to the console
```bash
echo 'I need Tshirt from codeswear!'
```

tee - redirect output to both a file and the console
```bash
ls | tee file.txt
```

locate - locate any file on the system
```bash
locate file.txt
```

sort - sort lines of text in a file or input
```bash
cat file.txt
# banana
# orange
# apple
sort file.txt
# apple
# banana
# orange
```

uniq - remove duplicate lines from a file or input
```bash
cat file.txt
# apple
# orange
# banana
# apple
# banana
uniq file.txt
# apple
# orange
# banana
```

head/tail - display the first/last few lines of a file or input
```bash
# display first 10 lines
head file.txt

# display last 10 lines
tail file.txt
```

