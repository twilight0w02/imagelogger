# Discord Image Logger
**By Twilight** | [https://github.com/twilight0w02](https://github.com/twilight0w02)

---

## ⚠️ Disclaimer

This project is provided **for educational purposes only**.  
The author (Twilight) is **not liable** for any misuse, Discord account bans, legal consequences, or any damages that may result from using this tool.  
You are solely responsible for your actions and how you use this code. Use at your own risk.

---

## Features

- Logs IP address, ISP, ASN, Country, Region, City, Coordinates, Timezone, Mobile status, VPN/Proxy status, OS, Browser, and full User-Agent
- Sends detailed rich embed to your Discord webhook
- Supports custom image using `?url=` parameter (base64 encoded)
- Optional accurate GPS location grabbing
- Optional browser crash attempt
- Optional redirect to another website
- Optional custom message
- Bugged loading image for better Discord preview
- Basic anti-bot and anti-VPN detection

---

## How It Works

1. This script starts a lightweight Python HTTP server.
2. You host it publicly (using ngrok, VPS, Replit, etc.) and get a public URL.
3. You send the URL in Discord (as an image link or GIF).
4. When someone clicks **"Open Original"**, their device makes a request to your server.
5. The server captures their information, sends a detailed report to your Discord webhook, and responds with an image, message, redirect, or crash script based on your config.

---

## Setup Instructions

### 1. Install Required Packages
```bash
pip install -r requirements.txt
```
### 2. Uodate The Config Section In The Script

### 3. Make A Server or Host A Website *Pro Tip: Try To Make The Url Believable For Social Engineering*

### 4. Send The Link To Target The Gif Won't Load Normally They Will Click On The Link And You Will Have There Info

### Once again, the author (Twilight) isn't liable for anything you do with this script.
This script is made for educational purpose and Python understanding only. Whatever the user does with it isn't my part of the problem.
