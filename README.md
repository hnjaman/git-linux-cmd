## Terminal Commands

### Basic Computer Operation

##### Linux user operation
Show all local user of your machine
```
cut -d: -f1 /etc/passwd
```
Add new user
```
sudo adduser username
# or
sudo useradd username
```
Add new user without password
```
adduser --disabled-password --gecos "" username
```
Grant root access to an user
```
sudo usermod -aG sudo username
```
Log in to other user
```
su username
```
Log out
```
exit
```
##### File permission

4 => stands for "read",

2 => stands for "write",

1 => stands for "execute", and

0 => stands for "no permission."

Read only permission 
```
chmod 4 id_rsa
```
All permission (4+2+1=7)
```
chmod 7 id_rsa
```
change ownership for directory and file to other user
```
sudo chown -R  hnj directory
sudo chown -R  hnj file.txt
```
Create a directory
```
mkdir DirectoryName
```
Rename directory
```
mv oldname newname
```
Move to the directory
```
cd DirectoryName
```
Move to hierarchical directory
```
cd DirectoryName/insideDirectoryName
```
Remove empty directory
```
rm -d DirectoryName
```
Remode non-empty directory
```
rm -r DirectoryName
```
Create new file
```
touch filename.txt 	# using touch

gedit filename.txt	# using gedit

cat > filename.txt	# using cat
```
Rename file  
```
mv old.txt new.txt
```
Remove file
```
rm filename.txt
```
Remove multiple file
```
rm file1.txt file2.txt
```
File open with gedit editor
```
gedit file.txt
```
File open with nano terminal editor
```
nano file.txt
```
Check terminal command history 
```
history
```
Save history in a text file
```
history > filename.txt
```

### Application running command

Maven Spring boot project
```
mvn spring-boot:run
```
Angular project
```
ng s --open
```
React project
```
yarn start
```
Rails project
```
rails s
```

### Linux terminal shortkeys

Open terminal
```
ctrl + alt + t
```
Linux terminal new tab
```
Ctrl + shift + t
```
Switch between different tabs 
```
alt + number # number=1,2,3...
```
Zoom in terminal fonts
``` 
ctrl + shift + (+)
```
Zoom out terminal fonts
```
ctrl + (-)
```

### Intellij IDE shortkeys

Run a java main program
```
ctrl + shift + f10
```
New class within project directory
```
alt + insert
```
New class within current package
```
ctrl + alt + insert
```
Find and jump to the desired class, file
```
ctrl + shift + n
```
Text search in all files 
```
ctrl + shift + f
```
Switch between intellij editor view to terminal 
```
alt + f12
```
New tab in intellij terminal
```
Ctrl + shift + t
```
