<div align="center">
  <h1>⚡ AMON-XMD ⚡</h1>
  <p><b>Next-Gen Multi-Device WhatsApp Bot engineered for speed, automation, and seamless group control.</b></p>
  <p><i>Proudly built in Kenya 🇰🇪 by Amon</i></p>

  <p>
    <a href="https://github.com/amondev254/AMON-XMD/stargazers"><img src="https://img.shields.io/github/stars/amondev254/AMON-XMD?style=for-the-badge&color=gold" alt="Stars"></a>
    <a href="https://github.com/amondev254/AMON-XMD/network/members"><img src="https://img.shields.io/github/forks/amondev254/AMON-XMD?style=for-the-badge&color=blue" alt="Forks"></a>
    <a href="https://github.com/amondev254/AMON-XMD/issues"><img src="https://img.shields.io/github/issues/amondev254/AMON-XMD?style=for-the-badge&color=red" alt="Issues"></a>
  </p>
</div>

---

## ✨ Features

* **🚀 Fast & Lightweight:** Built on Node.js & Baileys for low-latency responses.
* **🛡️ Group Management:** Anti-link, welcome/goodbye messages, kick/promote/demote, and group lock controls.
* **📥 Media Downloader:** Download videos, audio, and status updates effortlessly.
* **🎨 Sticker & Media Tools:** Convert images/videos to stickers, edit media, and more.
* **🤖 Smart Automation:** Auto-reply, auto-status view/react, and custom command prefixes.

---

## 🔗 Step 1: Fork & Get Session ID

1. **Fork this repository** by clicking the button below:
   <br>
   <a href="https://github.com/amondev254/AMON-XMD/fork">
     <img src="https://img.shields.io/badge/FORK%20REPOSITORY-000000?style=for-the-badge&logo=github&logoColor=white" alt="Fork Repo"/>
   </a>

2. **Generate your Session ID** using the official AMON-XMD Pairing Site:
   <br>
   <a href="https://access-key-tge1.onrender.com">
     <img src="https://img.shields.io/badge/GET%20SESSION%20ID%20(PAIR%20CODE)-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Pair Site"/>
   </a>
   > *Link: `https://access-key-tge1.onrender.com`*

---

## 🚀 Step 2: Deployment

### Option A: Deploy to Heroku
Click the button below, enter your `SESSION_ID` and config variables, and deploy:

<a href="https://heroku.com/deploy?template=https://github.com/amondev254/AMON-XMD">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy to Heroku"/>
</a>

### Option B: Deploy to Render / Koyeb / Panel
1. Fork this repository.
2. Create a new **Web Service** or **Worker** on your preferred host (Render, Koyeb, Railway, or Pterodactyl Panel).
3. Connect your forked `AMON-XMD` repository.
4. Set the required environment variables (see below) and start the bot.

### Option C: Local / Termux Installation
```bash
# Clone your forked repository
git clone [https://github.com/amondev254/AMON-XMD.git](https://github.com/amondev254/AMON-XMD.git)

# Enter project directory
cd AMON-XMD

# Install dependencies
npm install

# Start the bot
npm start
⚙️ Environment VariablesVariableDescriptionExampleSESSION_IDSession string obtained from the Pairing SiteAMON-XMD~xxxxPREFIXCommand trigger symbol. or !OWNER_NUMBERYour WhatsApp number with country code (no +)2547XXXXXXXXMODEBot access mode (public or private)public⚠️ DisclaimerThis bot is created for educational and personal automation purposes. Misuse of this tool (such as spamming) may result in your WhatsApp account being banned. The developer is not responsible for any account restrictions.
