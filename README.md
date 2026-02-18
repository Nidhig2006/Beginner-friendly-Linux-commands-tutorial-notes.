# 🐧 Linux Commands Tutorial Cheat Sheet

This is a beginner-friendly Linux command reference I made while learning Linux for cloud, DevOps, and cybersecurity.

---

## 📂 Navigation Commands

```bash
cd reports      # move into folder
cd ..           # go back one level
pwd             # show current directory
ls              # list files
ls -la          # detailed + hidden files
whoami          # current username
```

---

## 📖 Reading Files

```bash
cat file.txt        # show full file
head file.txt       # first 10 lines
tail file.txt       # last 10 lines
less file.txt       # scroll file
```

---

## 📁 File Management

```bash
mkdir project       # create folder
touch file.txt      # create file
cp file.txt backup/ # copy file
mv old.txt new.txt  # rename file
rm file.txt         # delete file
nano notes.txt      # edit file
```

---

## 🔎 Search & Filter

```bash
find . -name "*log*"   # search files
grep error log.txt     # search text
ls | grep test         # filter output
```

---

## 👤 User Management

```bash
sudo useradd user
sudo userdel user
sudo usermod -aG group user
sudo usermod -L user
```

---

## 🔐 Permissions

```bash
chmod u+rwx file.txt
sudo chown user file.txt
sudo chown :group file.txt
```

---

## 📚 Help Commands

```bash
man chmod
whatis nano
apropos password
```

---

## 💡 Notes

- Practice commands regularly.
- Be careful with delete commands.
- Permissions are important in security.

---

⭐ Created while learning Linux for Cloud, DevOps, and Cybersecurity.
# Beginner-friendly-Linux-commands-tutorial-notes.
A structured Linux command reference covering navigation, files, users, and permissions.
