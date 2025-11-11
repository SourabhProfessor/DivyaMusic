<h1 align="center">🎧 ──「 𝙎𝙋𝙊𝙏𝙄𝙁𝙔 ダ 𝙈𝙐𝙎𝙄𝘾 」── 🎵</h1>

<p align="center">
  <img src="https://files.catbox.moe/0d1eh1.jpg" width="500px" style="border-radius:15px;">
</p>

<p align="center">
<a href="https://github.com/BABY-MUSIC/JAZZY"><img src="https://img.shields.io/github/stars/BABY-MUSIC/JAZZY?color=black&logo=github&logoColor=black&style=for-the-badge" alt="Stars" /></a>
<a href="https://github.com/BABY-MUSIC/JAZZY/network/members"> <img src="https://img.shields.io/github/forks/BABY-MUSIC/JAZZY?color=black&logo=github&logoColor=black&style=for-the-badge" /></a>
<a href="https://github.com/BABY-MUSIC/JAZZY/blob/master/LICENSE"> <img src="https://img.shields.io/badge/License-MIT-blueviolet?style=for-the-badge" alt="License" /> </a>
<a href="https://www.python.org/"> <img src="https://img.shields.io/badge/Written%20in-Python-orange?style=for-the-badge&logo=python" alt="Python" /> </a>
<a href="https://github.com/BABY-MUSIC/JAZZY/commits/BABY-MUSIC"> <img src="https://img.shields.io/github/last-commit/BABY-MUSIC/JAZZY?color=blue&logo=github&logoColor=green&style=for-the-badge" /></a>
</p>

---

## 🚀 Deployment Options

### ☁️ Deploy on Koyeb
[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?name=spotify-music&type=git&repository=BABY-MUSIC%2FSPOTIFY_MUSIC&branch=main&builder=dockerfile)

### 💜 Deploy on Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?template=https://github.com/SourabhProfessor/DivyaMusic)

---

## ⚙️ Quick Setup Guide

Follow these simple steps to get your bot running in no time:

```bash
# 1️⃣ Upgrade and Update Packages
sudo apt-get update && sudo apt-get upgrade -y

# 2️⃣ Install Required Dependencies
sudo apt-get install python3-pip ffmpeg -y

# 3️⃣ Upgrade PIP
sudo pip3 install -U pip

# 4️⃣ Install Node.js (v18)
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
source ~/.bashrc
nvm install v18

# 5️⃣ Clone the Repository
git clone https://github.com/BABY-MUSIC/SPOTIFY_MUSIC && cd SPOTIFY_MUSIC

# 6️⃣ Install Python Requirements
pip3 install -U -r requirements.txt

# 7️⃣ Setup Environment Variables
cp sample.env .env
vi .env
# Press 'I' to edit → change your values → press Ctrl + C → type ':wq' to save

# 8️⃣ Install tmux (optional but recommended)
sudo apt install tmux -y && tmux

# 9️⃣ Run the Bot 🚀
bash start
