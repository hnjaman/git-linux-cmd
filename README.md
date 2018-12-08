## Terminal Commands

### Basic Computer Operation

#### Linux user operation
Show all local user
```
cut -d: -f1 /etc/passwd
```
add new user
```
sudo adduser username
```
add new user without password
```
adduser --disabled-password --gecos "" username
```
grant root access to an user
```
sudo usermod -aG sudo username
```
read only permission 
```
chmod 4 id_rsa
```
change permission for directory and file to other user
```
sudo chown -R  hnj directory
sudo chown -R  hnj file.txt
```
# Create a directory
mkdir DirectoryName

# Rename directory
mv oldname newname

# Move to the directory
cd DirectoryName

# Move to hierarchical directory
cd DirectoryName/insideDirectoryName

# Remove empty directory
rm -d DirectoryName

# Remode non-empty directory
rm -r DirectoryName

# Create file
touch filename.txt 	# using touch

gedit filename.txt	# using gedit

cat > filename.txt	# using cat

# Rename file  
mv old.txt new.txt

# Remove file
rm filename.txt

# Remove multiple file
rm file1.txt file2.txt

# File open with gedit editor
gedit file.txt

# File open with nano terminal editor
nano file.txt

# Check terminal command history 
history

# Save history in a text file
history > filename.txt

```

### Application running command

```
# Maven Spring boot
mvn spring-boot:run

# Angular
ng s --open

# React
yarn start

# rails 
rails s
```

### Linux terminal shortkeys

```
# Open terminal
ctrl + alt + t

# linux terminal new tab
Ctrl + shift + t

# switch between different tabs 
alt + number # number=1,2,3...

# Zoom in terminal 
ctrl + shift + (+)

# Zoom out terminal
ctrl + (-)
```

### Intellij IDE shortkeys

```
# Run a java main program
ctrl + shift + f10

# New class within project directory
alt + insert

# New class within current package
ctrl + alt + insert

# Find and jump to the desired class, file
ctrl + shift + n

# Text search in all files 
ctrl + shift + f

# switch between intellij editor view to terminal 
alt + f12

# new tab in intellij terminal
Ctrl + shift + t
```
