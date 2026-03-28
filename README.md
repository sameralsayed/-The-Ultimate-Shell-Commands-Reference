# 🐚 Ultimate Shell Commands Guide

[![Shell](https://img.shields.io/badge/Shell-Bash-blue?logo=gnubash)](https://www.gnu.org/software/bash/)
[![Linux](https://img.shields.io/badge/OS-Linux-yellow?logo=linux)](https://www.linux.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 📖 Description
A **comprehensive collection** of essential shell commands with **tutorials and practical examples**. Perfect for beginners, system administrators, and anyone who wants to master the command line. This guide covers file management, text processing, permissions, networking, processes, and more — all in one place.

## 🏷️ Tags
`shell` `bash` `linux` `command-line` `tutorial` `sysadmin` `productivity` `terminal` `unix`

## ✨ Features
- 🔍 Over **50 essential commands** explained
- 📘 **Tutorial-style** usage with real examples
- 🚀 Beginner‑friendly but useful for pros
- 📂 Organized by categories (files, text, processes, etc.)
- 🎨 Emojis for quick visual scanning
- 💡 Tips and common pitfalls

---

## 📚 How to Use This Guide
1. Browse the categories below.
2. Each command includes:
   - 🖍️ **Name** with an emoji
   - 📝 **Description**
   - 💻 **Syntax** and a **tutorial example**
3. Try the examples in your own terminal.
4. Use the `man` command (e.g., `man ls`) to explore deeper options.

---

## 📁 File & Directory Operations

| Command | Description |
|---------|-------------|
| 📂 `ls` | List directory contents. <br> 💻 `ls -la` → show all files with details. |
| 📁 `cd` | Change directory. <br> 💻 `cd /home/user` → go to `/home/user`. |
| 🧭 `pwd` | Print working directory. <br> 💻 `pwd` → shows current folder path. |
| 📂 `mkdir` | Create a new directory. <br> 💻 `mkdir projects` → create `projects` folder. |
| 🗑️ `rmdir` | Remove an empty directory. <br> 💻 `rmdir old_folder` → deletes empty folder. |
| ❌ `rm` | Remove files or directories. <br> 💻 `rm -rf temp/` → force remove `temp` and its contents. |
| 📄 `touch` | Create an empty file or update timestamp. <br> 💻 `touch notes.txt` → creates `notes.txt`. |
| 📋 `cp` | Copy files or directories. <br> 💻 `cp file1.txt file2.txt` → copies `file1` to `file2`. |
| ✂️ `mv` | Move or rename files/directories. <br> 💻 `mv oldname.txt newname.txt` → renames file. |

## 📄 Viewing & Editing Files

| Command | Description |
|---------|-------------|
| 📖 `cat` | Concatenate and display file content. <br> 💻 `cat file.txt` → prints whole file. |
| 📜 `less` | View file page by page. <br> 💻 `less large.log` → scroll with arrows, `q` to quit. |
| 📄 `head` | Show first lines of a file. <br> 💻 `head -n 20 file.txt` → first 20 lines. |
| 📄 `tail` | Show last lines of a file. <br> 💻 `tail -f log.txt` → follow new lines in real time. |
| ✏️ `nano` | Simple text editor. <br> 💻 `nano script.sh` → edit or create a file. |
| 📝 `echo` | Print text to stdout. <br> 💻 `echo "Hello World"` → displays message. |

## 🔍 Text Processing & Searching

| Command | Description |
|---------|-------------|
| 🔎 `grep` | Search for patterns in files. <br> 💻 `grep "error" app.log` → find lines containing "error". |
| 📊 `sed` | Stream editor for text transformation. <br> 💻 `sed 's/old/new/g' file.txt` → replace all `old` with `new`. |
| 📑 `awk` | Powerful text processing language. <br> 💻 `awk '{print $1}' file.txt` → print first column. |
| 🔄 `sort` | Sort lines of text. <br> 💻 `sort names.txt` → alphabetical order. |
| 🔁 `uniq` | Report or omit repeated lines. <br> 💻 `sort names.txt \| uniq -c` → count unique lines. |
| 📏 `wc` | Word, line, and character count. <br> 💻 `wc -l file.txt` → count lines. |

## 🔐 Permissions & Ownership

| Command | Description |
|---------|-------------|
| 🔒 `chmod` | Change file permissions. <br> 💻 `chmod 755 script.sh` → rwxr-xr-x permissions. |
| 👤 `chown` | Change file owner and group. <br> 💻 `chown user:group file.txt` → set owner and group. |
| 🔐 `umask` | Set default permissions for new files. <br> 💻 `umask 022` → default permissions 755 for dirs. |

## 🧵 Process Management

| Command | Description |
|---------|-------------|
| 📊 `ps` | Show running processes. <br> 💻 `ps aux` → detailed list of all processes. |
| 🔄 `top` | Interactive process viewer. <br> 💻 `top` → real-time system summary. |
| ⚡ `kill` | Terminate a process by PID. <br> 💻 `kill -9 1234` → forcefully kill process 1234. |
| 🧵 `jobs` | List background jobs. <br> 💻 `jobs` → show jobs in current shell. |
| 🏃 `bg` / `fg` | Resume jobs in background/foreground. <br> 💻 `bg %1` → send job 1 to background. |

## 🌐 Networking

| Command | Description |
|---------|-------------|
| 🌍 `ping` | Test network connectivity. <br> 💻 `ping google.com` → check reachability. |
| 📡 `curl` | Transfer data from/to a server. <br> 💻 `curl -I https://example.com` → fetch headers. |
| 🔌 `wget` | Download files from the web. <br> 💻 `wget https://example.com/file.zip` → download file. |
| 📡 `ssh` | Secure shell to remote machine. <br> 💻 `ssh user@192.168.1.10` → connect to remote host. |
| 📂 `scp` | Securely copy files over SSH. <br> 💻 `scp file.txt user@remote:/path/` → copy file to remote. |
| 🔄 `rsync` | Efficient file sync and transfer. <br> 💻 `rsync -avz ./local/ user@remote:/dest/` → sync directories. |
| 🔌 `netstat` | Network statistics and connections. <br> 💻 `netstat -tulpn` → show listening ports. |

## 🗜️ Compression & Archiving

| Command | Description |
|---------|-------------|
| 🗃️ `tar` | Archive multiple files. <br> 💻 `tar -czvf archive.tar.gz folder/` → create gzipped tar. |
| 🗜️ `gzip` / `gunzip` | Compress/decompress files. <br> 💻 `gzip largefile.txt` → creates `.gz` file. |
| 🗜️ `zip` / `unzip` | Work with zip archives. <br> 💻 `unzip archive.zip -d target/` → extract to target. |

## ⚙️ Shell Environment & Scripting

| Command | Description |
|---------|-------------|
| 🔧 `export` | Set environment variables. <br> 💻 `export PATH=$PATH:/my/bin` → add directory to PATH. |
| 🧩 `alias` | Create command shortcuts. <br> 💻 `alias ll='ls -alF'` → `ll` shows detailed listing. |
| 📜 `history` | Show command history. <br> 💻 `history 10` → last 10 commands. |
| 🧠 `source` | Execute commands from a file in current shell. <br> 💻 `source ~/.bashrc` → reload bash configuration. |
| 🔁 `for` / `while` | Loops in shell scripts. <br> 💻 `for i in {1..5}; do echo $i; done` → prints 1 to 5. |
| ❓ `if` | Conditional execution. <br> 💻 `if [ -f file.txt ]; then echo "exists"; fi` → check if file exists. |

## 🛠️ System Information

| Command | Description |
|---------|-------------|
| 🖥️ `uname` | Print system information. <br> 💻 `uname -a` → all kernel details. |
| 💾 `df` | Disk space usage. <br> 💻 `df -h` → human-readable sizes. |
| 📊 `du` | Estimate file/directory space. <br> 💻 `du -sh *` → total size of each item. |
| 🧠 `free` | Memory usage. <br> 💻 `free -h` → human-readable RAM info. |
| 📅 `date` | Display or set system date/time. <br> 💻 `date +"%Y-%m-%d"` → output: 2025-03-28. |

---

## 📘 Tutorial: Building a Simple Shell Script
1. Create a file:  
   💻 `touch my_script.sh`
2. Make it executable:  
   💻 `chmod +x my_script.sh`
3. Edit with nano:  
   💻 `nano my_script.sh`
4. Add shebang and code:
   ```bash
   #!/bin/bash
   echo "Hello, $(whoami)! Today is $(date)."
