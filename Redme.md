# Linux / WSL Command Reference

This README contains commonly used Linux commands with their purpose.

---

## 📁 Directory & File Commands

pwd  
→ Show current working directory

ls  
→ List files and folders

ls -la  
→ List all files with details (including hidden files)

cd foldername  
→ Move into a directory

cd ..  
→ Go back one directory

mkdir foldername  
→ Create a new folder

rmdir foldername  
→ Delete an empty folder

touch file.txt  
→ Create a new empty file

rm file.txt  
→ Delete a file

rm -r foldername  
→ Delete a folder with contents

cp source destination  
→ Copy files or folders

mv source destination  
→ Move or rename files

---

## 📝 File Reading & Writing

nano file.txt  
→ Open file to write or edit

cat file.txt  
→ Read file content

less file.txt  
→ Read long file with scrolling

echo "text" > file.txt  
→ Write text to file (overwrite)

echo "text" >> file.txt  
→ Append text to file

cat file1.txt file2.txt > merged.txt  
→ Merge two files into one

---

## 🔍 Search & Text Processing

grep "word" file.txt  
→ Search for a word in a file

wc -l file.txt  
→ Count number of lines

sort file.txt  
→ Sort file content

uniq file.txt  
→ Remove duplicate lines

---

## 🔐 Permissions

chmod +x script.sh  
→ Make a script executable

chmod 755 file.sh  
→ Set file permissions

---

## 📦 Package Management

sudo apt update  
→ Update package list

sudo apt upgrade  
→ Upgrade installed packages

sudo apt install package-name  
→ Install a package

sudo apt remove package-name  
→ Remove a package

---

## ⚙️ System & Process

ps aux  
→ Show running processes

top  
→ Display running processes live

kill PID  
→ Stop a process

df -h  
→ Show disk usage

free -h  
→ Show memory usage

---

## 🌐 Network

ip a  
→ Show network interfaces

ping google.com  
→ Test internet connection

---

## 🧠 History & Help

history  
→ Show command history

man command  
→ Show manual for a command

command --help  
→ Show help for a command

---

## 🐚 Shell Script

#!/bin/bash  
→ Shebang line for bash script

chmod +x script.sh  
→ Give execute permission

./script.sh  
→ Run shell script

---

## 🚪 Exit

exit  
→ Exit terminal or WSL

