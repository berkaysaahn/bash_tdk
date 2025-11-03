# bash_tdk

A simple terminal tool to query word meanings directly from the **Turkish Language Association (TDK)**.  
It lets you quickly look up unknown words right from your terminal.

---

## ⚙️ Dependencies
- curl
- jq
If these are not installed, you can install them on Linux with:
```bash
sudo pacman -S curl jq    # For Arch-based systems
# or
sudo apt install curl jq  # For Debian/Ubuntu
```

---

## 🗂️ Installation
1. Clone the repository:
```bash
git clone https://github.com/berkaysaahn/bash_tdk.git
```
2. Enter the directory:
```bash
cd bash/tdk
```
3. Make the script executable:
```bash
chmod +x tdk
```
4. (Optional) Add it to your PATH for global access:
```bash
sudo cp tdk /usr/local/bin
```

---

## 🧠 Usage
- if the script is added to the PATH:
```bash
tdk <word>
```
- if the script is not added to the PATH:
```bash
cd bash_tdk
./tdk <word>
```

