# MS TEAM — Ruijie Voucher Finder Bot

Telegram bot for finding Ruijie WiFi vouchers.

## ✨ Features
- Auto captcha solving (OCR)
- Multi-digit scan (6, 7, 8, all, ascii-lower)
- Real-time progress
- Success + Limited codes tracking
- Local persistence (JSON)

## 📦 Requirements
- Python 3.9+
- Termux (Android) or Ubuntu/Debian

## 🚀 Installation

### Termux (Android)
```bash
pkg update && pkg upgrade -y
pkg install proot-distro -y
proot-distro install ubuntu
proot-distro login ubuntu

apt update && apt install python3 python3-pip libgl1 libglib2.0-0 git tmux -y
pip3 install --upgrade pip
pip3 install pyTelegramBotAPI aiohttp opencv-python-headless ddddocr numpy --break-system-packages
