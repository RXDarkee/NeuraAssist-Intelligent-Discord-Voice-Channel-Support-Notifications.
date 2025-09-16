# 🎧 Discord Support Voice Bot

> A modern, smart Discord bot for **FiveM servers**, **support communities**, and **gaming hubs**. It auto-welcomes users joining a voice support channel and alerts your staff team privately with full user info. Fully automated, sleek, and easy to use.

![Banner](https://cdn.discordapp.com/attachments/1414649473849884742/1417028724146311218/raw.png?ex=68caf896&is=68c9a716&hm=e4d635429e19c2d2d27038cc769bcedc4126c246366860d4dc7dc666d680ee22&)

---

## 📌 Key Features

- ✅ Sends a stylish **welcome embed** to users joining the support voice channel
- 🚨 Privately alerts staff with full **user details, avatar, join dates, and jump links**
- **🧹 Automatically deletes all messages when the user leaves**
- 🎨 Clean, animated, and fully **embedded messages**
- 🔒 Validates configuration on startup (token, server ID, role, voice channel)
- ⚡ Lightweight, fast, async-powered with `discord.py`

---

## 🧠 Ideal For

- 🚓 **FiveM RP Servers** – whitelisting, mod support, interviews, and admin help
- 🎮 **Gaming Servers** – auto staff ping for tech support or community guidance
- 🧰 **Tech Support Communities** – help desks and issue tracking via voice
- 💬 **Any Discord Server** needing automated voice channel monitoring

---

## 🎬 YouTube Demo

📺 **Watch the bot in action on YouTube:**  
[![Watch Now](https://img.shields.io/badge/Watch%20on-YouTube-red?style=for-the-badge&logo=youtube)](https://your-youtube-link.com)



---

## **🖼️ Embed Previews**
👋 Welcome DM to User
Automatically sent when a user joins the support VC.
Includes: greeting, instructions, image, and jump link.


## **👮 Alert DM to Staff/Admin**
Sent to each staff/admin member with a specific role.
Includes: user mention, join date, account creation, channel link, and avatar.


📂 Project Structure

``` 📁 discord-support-voice-bot
│
├── bot.py                # Main bot logic
├── .env                  # Environment variables (excluded from GitHub)
└── requirements.txt      # Python dependencies
```

###### **👤 Credits**

  👨‍💻 Developed by: Rasan Fernando 

  🎨 Bot Design & UX: Custom banners, embeds, and logic by Rasan

  💬 Special Thanks: All staff testers and Support Discord

  🛠️ Powered by: discord.py, Python 3.11+

## **📜 License & Usage**

This project is free for personal use, but:

✅ Credit must be given to the developer.

❌ No re-selling or uploading without permission.

✅ You’re free to fork, remix, and contribute.

**⭐ Support This Project**
If this bot helped your server or saved your time, please consider:

⭐ Starring the repo

📢 Sharing with other FiveM/Gaming/Support server owners

❤️ Giving credit where it’s due

<h3 align="center">📸 Screenshots</h3>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1417600725332131993/1417600879636381816/image.png?ex=68cb1333&is=68c9c1b3&hm=2dce623dcfc83c70965d249f8d8bbba6b1de8ca9fbafd25e56d9571f62d4ca31&" alt="User Welcome Screenshot" width="45%" />
  <img src="https://cdn.discordapp.com/attachments/1417600743166181376/1417601539522170900/image.png?ex=68cb13d0&is=68c9c250&hm=68b97151ffb18222a754513790c8f2a3707ac4960b674a12f248a2de3c21bfbb&" alt="Staff Alert Screenshot" width="45%" />
</p>

<p align="center">
  <b>👤 Left: User Welcome Embed &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp; 🔔 Right: Staff Member Alert Embed</b>
</p>
## ⚙️ Setup Guide

## **1. 📥 Clone the Repo**

```bash
git clone https://github.com/RXDarkee/discord-support-voice-bot.git
cd discord-support-voice-bot
pip install -r requirements.txt
python bot.py
```
