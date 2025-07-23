# Sybau

Sybau

A minimal Linux package that immediately shuts your PC's B***h A** up when executed.  
Intended for scripting, automation, or fun — **not** for accidental use.

> ⚠️ This will power off your system immediately. Be careful!

---

## 🚀 Features

- One-liner shutdown
- Can be installed as a package on Arch Linux
- Works with `systemctl` under most modern Linux distros

---

## 🛠️ Installation

### 📦 For Arch Linux / Manjaro users:

```bash
git clone https://github.com/YOUR_USERNAME/shutdown-now.git
cd shutdown-now
makepkg -si
```

You can now run:

```bash
Sybau
```
And your system will immediately shut down.

You may need sudo permissions or appropriate PolicyKit rules for systemctl poweroff.

🔧 How It Works
The script simply runs:

```bash
systemctl poweroff
```
You can find the script here: Sybau.sh

