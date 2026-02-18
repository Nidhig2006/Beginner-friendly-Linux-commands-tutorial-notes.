# 🐧 Linux Commands Tutorial Cheat Sheet

This is a beginner-friendly Linux command reference I made while learning Linux for cloud, DevOps, and cybersecurity.

---

## 📂 Navigation Commands

### `cd reports`
```bash
cd reports
```
Moves into the **reports** directory from the current location.

---

### `cd ..`
```bash
cd ..
```
Moves one directory level up.

---

### `pwd`
```bash
pwd
```
Displays the full path of the current working directory.

---

### `ls`
```bash
ls
```
Lists files and directories in the current directory.

---

### `ls -la`
```bash
ls -la
```
Shows detailed information including permissions, owner, hidden files, and timestamps.

---

### `whoami`
```bash
whoami
```
Displays the username of the currently logged-in user.

---

## 📖 Reading Files

### `cat file.txt`
```bash
cat file.txt
```
Displays the entire content of a file.

---

### `head file.txt`
```bash
head file.txt
```
Shows the first 10 lines of a file.

---

### `tail file.txt`
```bash
tail file.txt
```
Shows the last 10 lines of a file.

---

### `less file.txt`
```bash
less file.txt
```
Opens the file in scrollable mode.  
Press `q` to exit.

---

## 📁 File Management

### `mkdir project`
```bash
mkdir project
```
Creates a new directory named **project**.

---

### `touch file.txt`
```bash
touch file.txt
```
Creates an empty file.

---

### `cp file.txt backup/`
```bash
cp file.txt backup/
```
Copies a file to another directory without deleting the original.

---

### `mv old.txt new.txt`
```bash
mv old.txt new.txt
```
Renames or moves a file.

---

### `rm file.txt`
```bash
rm file.txt
```
Deletes a file permanently.  
⚠ Use with caution.

---

### `nano notes.txt`
```bash
nano notes.txt
```
Opens a file in the Nano text editor.

Useful shortcuts:
- `Ctrl + O` → Save
- `Ctrl + X` → Exit

---

## 🔎 Search & Filtering

### `find . -name "*log*"`
```bash
find . -name "*log*"
```
Searches for files containing **log** in their name.

---

### `grep error log.txt`
```bash
grep error log.txt
```
Searches for the word **error** inside a file.

---

### `ls | grep test`
```bash
ls | grep test
```
Filters output using a pipe (`|`).

---

## 👤 User Management

### Add a User
```bash
sudo useradd user
```
Creates a new user account.

---

### Delete a User
```bash
sudo userdel user
```
Deletes an existing user.

---

### Add User to Group
```bash
sudo usermod -aG group user
```
Adds a user to an additional group.  
⚠ Always use `-a` with `-G`.

---

### Lock User Account
```bash
sudo usermod -L user
```
Disables user login.

---

## 🔐 Permissions & Ownership

### Change File Permissions
```bash
chmod u+rwx file.txt
```
Gives read, write, and execute permissions to the user.

---

### Change File Owner
```bash
sudo chown user file.txt
```
Changes the owner of a file.

---

### Change Group Owner
```bash
sudo chown :group file.txt
```
Changes the group ownership of a file.

---

## 📚 Help Commands

### Manual Page
```bash
man chmod
```
Displays detailed documentation for a command.

---

### Quick Description
```bash
whatis nano
```
Shows a one-line description of a command.

---

### Search Commands
```bash
apropos password
```
Finds commands related to a keyword.

---



⭐ Created while learning Linux for Cybersecurity.

