<div align="center">
  <img src="https://i.ibb.co/G4f0D721/img-0pyiocoxw4.jpg" alt="AMON-XMD Banner" width="100%" />

  <a href="https://github.com/amondev254">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=25D366&center=true&vCenter=true&width=600&lines=AMON-XMD+WHATSAPP+BOT;500%2B+COMMANDS+%7C+AI+POWERED;BUILT+IN+KENYA+%F0%9F%87%B0%F0%9F%87%AA+BY+AMON" alt="AMON-XMD Typing SVG" />
  </a>

  <p><b>Next-Gen Multi-Device WhatsApp Bot engineered for speed, automation, and seamless group control.</b></p>
  <p><i>Proudly built in Kenya 🇰🇪 by Amon</i></p>

  <p>
    <a href="https://github.com/amondev254/AMON-XMD/stargazers"><img src="https://img.shields.io/github/stars/amondev254/AMON-XMD?style=for-the-badge&color=gold" alt="Stars"></a>
    <a href="https://github.com/amondev254/AMON-XMD/network/members"><img src="https://img.shields.io/github/forks/amondev254/AMON-XMD?style=for-the-badge&color=blue" alt="Forks"></a>
    <a href="https://github.com/amondev254/AMON-XMD/issues"><img src="https://img.shields.io/github/issues/amondev254/AMON-XMD?style=for-the-badge&color=red" alt="Issues"></a>
    <a href="https://github.com/amondev254/AMON-XMD/blob/main/LICENSE"><img src="https://img.shields.io/github/license/amondev254/AMON-XMD?style=for-the-badge&color=green" alt="License"></a>
  </p>

  <p>
    <a href="https://whatsapp.com/channel/0029VbDyZnG7NoZzRQbTHY0z">
      <img src="https://img.shields.io/badge/WHATSAPP%20CHANNEL-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp Channel"/>
    </a>
  </p>
</div>

---

## ✨ Features

* **🚀 Fast & Lightweight:** Built on Node.js & Baileys for low-latency responses with zero lag.
* **🛡️ Group Management:** Anti-link, anti-tag, anti-bot, anti-spam, anti-badword, welcome/goodbye messages, kick/promote/demote, and group lock controls.
* **📥 Media & Sticker Tools:** Download media, auto-convert images/videos to stickers, and customize sticker pack names.
* **🤖 Smart Automation:** Auto-read, auto-typing, auto-bio, auto-react, auto-download, chatbot toggle, and customizable prefix.

---

## 🎛️ Panel Deployment Guideline

<div align="center">
  <a href="https://github.com/amondev254/AMON-XMD/archive/refs/heads/main.zip">
    <img src="https://img.shields.io/badge/BOT%20FILE%20DOWNLOAD-2563EB?style=for-the-badge&logo=github&logoColor=white" alt="Bot File Download"/>
  </a>
  <a href="https://access-key-tge1.onrender.com">
    <img src="https://img.shields.io/badge/SESSION%20ID%20SITE-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Session ID Site"/>
  </a>
  <a href="https://rl.katabump.fr/964263">
    <img src="https://img.shields.io/badge/PANEL%20LINK-7C3AED?style=for-the-badge&logo=server&logoColor=white" alt="Panel Link"/>
  </a>
</div>

<br>

1. Click **Bot File Download** above to download the bot archive to your device.
2. Click **Session ID Site** above to generate and copy your `SESSION_ID`.
3. Click **Panel Link** above to open your hosting panel, create a **Node.js** server, and upload & extract the bot archive.
4. Open **`setting.js`** in your panel file manager and set:
   * `ownerNumber`: Your number without `+` or spaces (e.g., `['254759XXXXXXXX']`)
   * `ownerName`: Your preferred name (e.g., `['Amon']`)
   * `sessionID`: Paste your generated session ID
5. Save **`setting.js`**, install dependencies if needed (`npm install`), and click **Start / Run** on your panel.

---

## 🚀 Other Deployment Options

<div align="center">
  <a href="#vps-deployment-ubuntu--debian-with-pm2">
    <img src="https://img.shields.io/badge/VPS%20SERVER-0EA5E9?style=for-the-badge&logo=linux&logoColor=white" alt="VPS Server"/>
  </a>
  <a href="https://heroku.com/deploy?template=https://github.com/amondev254/AMON-XMD">
    <img src="https://img.shields.io/badge/HEROKU-430098?style=for-the-badge&logo=heroku&logoColor=white" alt="Heroku"/>
  </a>
  <a href="#render--koyeb--railway">
    <img src="https://img.shields.io/badge/RENDER-46E3B7?style=for-the-badge&logo=render&logoColor=black" alt="Render"/>
  </a>
  <a href="#render--koyeb--railway">
    <img src="https://img.shields.io/badge/KOYEB-121212?style=for-the-badge&logo=koyeb&logoColor=white" alt="Koyeb"/>
  </a>
  <a href="#render--koyeb--railway">
    <img src="https://img.shields.io/badge/RAILWAY-0B0D0E?style=for-the-badge&logo=railway&logoColor=white" alt="Railway"/>
  </a>
  <a href="#local--termux-installation">
    <img src="https://img.shields.io/badge/TERMUX-10B981?style=for-the-badge&logo=gnubash&logoColor=white" alt="Termux"/>
  </a>
</div>

<br>

### VPS Deployment (Ubuntu / Debian with PM2)
<img src="https://img.shields.io/badge/UBUNTU-E95420?style=flat-square&logo=ubuntu&logoColor=white" alt="Ubuntu"/> <img src="https://img.shields.io/badge/DEBIAN-A81D33?style=flat-square&logo=debian&logoColor=white" alt="Debian"/> <img src="https://img.shields.io/badge/PM2-2B037A?style=flat-square&logo=pm2&logoColor=white" alt="PM2"/>

```bash
# Update system & install Node.js (v20+), Git, and FFmpeg
sudo apt update && sudo apt upgrade -y
curl -fsSL [https://deb.nodesource.com/setup_20.x](https://deb.nodesource.com/setup_20.x) | sudo -E bash -
sudo apt install -y nodejs git ffmpeg

# Clone the repository
git clone [https://github.com/amondev254/AMON-XMD.git](https://github.com/amondev254/AMON-XMD.git)
cd AMON-XMD

# Install dependencies
npm install

# Edit setting.js with your ownerNumber, ownerName, and sessionID
nano setting.js

# Install PM2 globally and keep AMON-XMD running 24/7
sudo npm install -g pm2
pm2 start index.js --name "amon-xmd"
pm2 save
pm2 startup
```

### Render / Koyeb / Railway
1. Create a new **Web Service** or **Background Worker** on your chosen platform.
2. Connect the repository and set your environment variables (`SESSION_ID`, etc.).
3. Deploy and monitor logs until connected.

### Local / Termux Installation
<img src="https://img.shields.io/badge/TERMUX-10B981?style=flat-square&logo=gnubash&logoColor=white" alt="Termux"/> <img src="https://img.shields.io/badge/NODE.JS-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js"/>

```bash
# Clone the repository
git clone [https://github.com/amondev254/AMON-XMD.git](https://github.com/amondev254/AMON-XMD.git)

# Enter project directory
cd AMON-XMD

# Install dependencies
npm install

# Edit setting.js with your number, name, and session ID, then start
npm start
```

---

## ⚙️ `setting.js` Configuration Guide

```javascript
ownerNumber: ['254118476518'], // Number without + or spaces
ownerName: ['Amon'],           // Your name
botName: 'AMON-XMD',
prefix: '.',
sessionID: process.env.SESSION_ID || 'PASTE_YOUR_SESSION_ID_HERE',
selfMode: false,               // true = owner only, false = public
timezone: 'Africa/Nairobi',
```

| Field / Env Var | Description | Example |
| :--- | :--- | :--- |
| `ownerNumber` | Owner number(s) without `+` or spaces | `['254759XXXXXXXX']` |
| `ownerName` | Owner display name(s) | `['Amon']` |
| `sessionID` / `SESSION_ID` | Session string from **Session ID Site** | `AMON-XMD~xxxx` |
| `prefix` | Command trigger symbol | `.` |
| `selfMode` | `false` for public mode, `true` for owner-only mode | `false` |

---

## 📄 License

<div align="center">
  <a href="https://github.com/amondev254/AMON-XMD/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/MIT%20LICENSE-16A34A?style=for-the-badge&logo=open-source-initiative&logoColor=white" alt="MIT License"/>
  </a>
</div>

---

## ⚠️ Disclaimer

This bot is created for educational and personal automation purposes. Misuse of this tool (such as spamming) may result in your WhatsApp account being banned. The developer is not responsible for any account restrictions.

---

<div align="center">
  <p>Made with ❤️ in Kenya 🇰🇪 by <b>Amon</b></p>
  <a href="https://whatsapp.com/channel/0029VbDyZnG7NoZzRQbTHY0z">
    <img src="https://img.shields.io/badge/FOLLOW%20WHATSAPP%20CHANNEL-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Follow WhatsApp Channel"/>
  </a>
  <a href="https://github.com/amondev254">
    <img src="https://img.shields.io/badge/OWNER%20-%20AMON%20(KENYA)-181717?style=for-the-badge&logo=github&logoColor=white" alt="Owner Amon"/>
  </a>
</div>
