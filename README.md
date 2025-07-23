# Sybau

Sybau

A minimal Linux package that immediately shuts your PC's B___h A$$ up when executed.  
Intended for scripting, automation, or fun — **not** for accidental use.

> ⚠️ This will power off your system immediately. Be careful!

---

## 🚀 Features

- One-liner shutdown
- Can be installed as a package on Arch Linux
- Works with `systemctl` under most modern Linux distros

---

## 🛠️ Installation

Just clone the repo and run ```makepkg -si```

### 📦 For Arch Linux / Manjaro users:

```bash
git clone https://github.com/Arshdeep-singh-chahal/Sybau.git
cd Sybau
makepkg -si
```

You can now run:

```bash
sybau
```
And your system will immediately shut down.

You may need sudo permissions or appropriate PolicyKit rules for systemctl poweroff.

🔧 How It Works
The script simply runs:

```bash
systemctl poweroff
```
You can find the script here: Sybau.sh

## 📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

## 🧠 Author
Arshdeep Singh
Feel free to fork or contribute if you want to build weird Linux utilities like this 

##🙅‍♂️ Disclaimer
I am not responsible for any data loss, system crashes, or rage quits caused by this script. Use at your own risk.
