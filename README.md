# Linux - Notes

✅ **What is Linux?** <br>

 - Linux is an open-source operating system based on Unix.  <br>
 - It is widely used in servers, desktops, mobile devices, and embedded systems.  <br>
 - Created by Linus Torvalds in 1991.  <br>

<hr>

🔧 **Key Features of Linux**  <br>

 - Open Source – Free to use and modify.  <br>
 - Multitasking – Can run multiple programs at the same time.  <br>
 - Multi-user – Multiple users can use the system simultaneously.  <br>
 - Security – Strong user permissions and encryption features.  <br>
 - Portability – Runs on different hardware types.  <br>

<hr>

🗃️ **Popular Linux Distributions (Distros)**

 - Ubuntu – Beginner-friendly, desktop-focused.
 - Debian – Stable, base for many distros.
 - Fedora – Cutting-edge, Red Hat-based.
 - CentOS / RHEL – Enterprise-focused.
 - Kali Linux – Security and penetration testing. 
 - Arch Linux – Advanced users, minimal setup.

<hr>

💻 **Linux Architecture**

 - Kernel – Core of the OS, manages hardware.
 - Shell – Interface between user and kernel.
 - Utilities – Command-line tools and programs.
 - File System – Organizes and stores data.

<hr>

🔐 **File Permissions**

Linux uses 3 types of access:  <br>
 - Read (r) – View contents  <br>
 - Write (w) – Modify contents  <br>
 - Execute (x) – Run file  <br>

 **File permission format example:**
 ```ssh
-rwxr-xr--
```

This shows :  <br>
 - Owner has full access (rwx)  <br>
 - Group can read and execute  <br>
 - Others can only read  <br>

<hr>

📦 **Package Management**

 - Debian-based (Ubuntu) : apt, dpkg
   - Example : sudo apt install nginx

 - RedHat-based (Fedora/CentOS) : yum, dnf, rpm
   - Example : sudo dnf install nginx

<hr>
  
🧠 **Process Management**

 - ps – Show running processes
 - top / htop – Interactive process viewer
 - kill – Stop process by PID
 - & – Run command in background
 - jobs, fg, bg – Job control

<hr>

📄 **Networking Commands**

| Command             | Description                   |
| ------------------- | ----------------------------- |
|  ifconfig /  ip a   | Show IP addresses             |
|  ping               | Check connectivity            |
|  netstat            | Show network connections      |
|  ss                 | Newer alternative to netstat  |
|  scp  /  rsync      | Secure file transfer          |
|  ssh                | Secure shell to remote system |

<hr>

🧪 **Shell Scripting (Basics)**

Shell scripts are saved with **.sh** and run using:  
```ssh
bash script.sh
```

Simple script: <br>
```ssh
#!/bin/bash
echo "Hello, $USER"
```

<hr>

⏱️ **Startup and Services**

 - systemctl – Manage system services  <br>
  - Example : sudo systemctl start apache2  <br>
 - cron – Schedule tasks  <br>
  - Edit with : crontab -e  <br>

<hr>

🛠️ **Common Admin Tasks**

 - User management : adduser, passwd, deluser  <br>
 - Disk usage : df, du  <br>
 - Searching : grep, find, locate  <br>
 - Logs : Located in /var/log/  <br>

<hr>
