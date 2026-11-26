# 🚀 Installation Guide

## Quick Install

### Windows
```bash
# 1. Install Python 3.7+ from python.org
# 2. Open Command Prompt or PowerShell

# Clone repository
git clone https://github.com/W8SOJIB/W8CameraScannerV1.git
cd W8CameraScannerV1

# Install dependencies
pip install -r requirements.txt

# Run
python W8CameraScanner.py
```

### Linux (Ubuntu/Debian)
```bash
# Update system
sudo apt update && sudo apt upgrade -y

# Install Python and pip
sudo apt install python3 python3-pip git -y

# Clone repository
git clone https://github.com/W8SOJIB/W8CameraScannerV1.git
cd W8CameraScannerV1

# Install dependencies
pip3 install -r requirements.txt

# Run
python3 W8CameraScanner.py
```

### Kali Linux
```bash
# Update system
sudo apt update

# Install dependencies
sudo apt install python3 python3-pip -y

# Clone repository
git clone https://github.com/W8SOJIB/W8CameraScannerV1.git
cd W8CameraScannerV1

# Install Python packages
pip3 install -r requirements.txt

# Run
python3 W8CameraScanner.py
```

### Termux (Android)
```bash
# Update packages
pkg update && pkg upgrade -y

# Install required packages
pkg install python git inetutils -y

# Clone repository
git clone https://github.com/W8SOJIB/W8CameraScannerV1.git
cd W8CameraScannerV1

# Install dependencies
pip install -r requirements.txt

# Run
python W8CameraScanner.py
```

### macOS
```bash
# Install Homebrew if not installed
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# Install Python
brew install python3

# Clone repository
git clone https://github.com/W8SOJIB/W8CameraScannerV1.git
cd W8CameraScannerV1

# Install dependencies
pip3 install -r requirements.txt

# Run
python3 W8CameraScanner.py
```

---

## Manual Installation

If you can't use git:

### 1. Download ZIP
- Go to: https://github.com/W8SOJIB/W8CameraScannerV1
- Click "Code" → "Download ZIP"
- Extract the ZIP file

### 2. Install Python
- Download from: https://www.python.org/downloads/
- Install Python 3.7 or higher

### 3. Install Colorama
```bash
pip install colorama
```

### 4. Run
```bash
python W8CameraScanner.py
```

---

## Troubleshooting

### "pip: command not found"
**Windows:**
```bash
python -m pip install -r requirements.txt
```

**Linux:**
```bash
sudo apt install python3-pip
```

### "Permission denied" (Linux/Mac)
```bash
sudo python3 W8CameraScanner.py
```

### "colorama not found"
```bash
pip install --upgrade colorama
# or
pip install colorama --user
```

### Traceroute not found (Linux/Termux)
```bash
# Termux
pkg install inetutils

# Ubuntu/Debian
sudo apt install traceroute

# Arch
sudo pacman -S traceroute
```

---

## Verification

After installation, verify by running:
```bash
python W8CameraScanner.py
```

You should see:
```
╔═══════════════════════════════════════╗
║   IP Range Camera Scanner             ║
║   W8Team - IP Scanner                 ║
║   Credit: W8Team/W8SOJIB              ║
╚═══════════════════════════════════════╝
```

✅ If you see this, installation is successful!

---

## Need Help?

- Create an issue: https://github.com/W8SOJIB/W8CameraScannerV1/issues
- Check README.md for full documentation

---

**Happy Scanning! 🚀**

