# Windows-11.99
A new release of Windows 10.99 create by Kings Windows 10 mixed with 11 all item only there is no way to install application or files 

# pictures
<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/19c2b400-8951-4807-b89f-adecf1717cbf" />

<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/750cdd24-49d8-488f-b428-7c0339dcc9be" />

<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/6cc9afd7-f523-4b4f-9f21-d80b911c3a07" />
commads use on termux app

---

## 🔧 Commands

```bash
# 1. Update Termux packages
pkg update -y && pkg upgrade -y
```
# users

```
pkg install git -y
pkg install wget -y

```
# 3. Clone the Windows 11.99 repository
```
git clone https://github.com/Adrianoplayer/Windows-11.99.git

```
# 4. Enter the cloned folder
```
cd Windows-11.99

```
# setup bash
```
bash setup.sh
```
# 🖥️ Run Windows 11.99 with VNC (on Termux)
```
```
This setup lets you run a graphical Windows-like desktop environment inside Termux and access it through **VNC Viewer**.
```
---
```
## 🔧 Commands
```
```bash
```
# 1. Update Termux packages
```
pkg update -y && pkg upgrade -y
```
# 2. Install required dependencies
```
pkg install git wget proot-distro -y
```
# 3. Install Ubuntu as base system
```
proot-distro install ubuntu
```
# 4. Login into Ubuntu
```
proot-distro login ubuntu
```
# 5. Inside Ubuntu: install the desktop and VNC server
```
```
apt update && apt upgrade -y
apt install xfce4 xfce4-goodies tightvncserver -y
```
# 6. Start the VNC server
```
vncserver :1
```
```
# (Default port: 5901 → use address 127.0.0.1:5901 in VNC Viewer)
```
