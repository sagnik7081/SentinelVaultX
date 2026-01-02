<div align="center">

# 🎪 SentinelVaultX an ATM Security System 🚨🔒

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=2000&pause=500&color=FF6B35&center=true&vCenter=true&multiline=true&width=800&height=120&lines=🤖+BEEP+BOOP!+DETECTING+FACES!+🤖;👁️+WATCHING+YOU+ALWAYS!+👁️" alt="Typing SVG" />

<div style="font-size: 20px; margin: 20px 0;">
 ╔══════════════════════════════╗<br>
 ║  👁️‍🗨️  FACE DETECTION ACTIVE  👁️‍🗨️  ║<br>
 ║    🔍 SCANNING... SCANNING... 🔍    ║<br>
 ║      🚨 SECURITY ENGAGED 🚨      ║<br>
 ╚══════════════════════════════╝
</div>

<p align="center">
🔍 📸 🔍 📱 🔍 📸 🔍
</p>

<p align="center">
<img src="https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python&logoColor=white&labelColor=306998">
<img src="https://img.shields.io/badge/Flask-2.0+-green?style=for-the-badge&logo=flask&logoColor=white&labelColor=000000">
<img src="https://img.shields.io/badge/OpenCV-4.0+-red?style=for-the-badge&logo=opencv&logoColor=white&labelColor=5C3EE8">
<img src="https://img.shields.io/badge/SQLite-3.0+-orange?style=for-the-badge&logo=sqlite&logoColor=white&labelColor=003B57">
<img src="https://img.shields.io/badge/InsightFace-AI-purple?style=for-the-badge&logo=tensorflow&logoColor=white&labelColor=FF6F00">
</p>

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">

</div>

---

## 🎨 Overview 📝

<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="400">

</div>

> 🎪 **Step right up to the greatest show in security!** 🎪  
> 
> Welcome to the most **entertaining**, **cartoon-powered**, **emoji-filled** ATM security system you've ever laid eyes on! This isn't just facial recognition — it's a **full-blown security carnival** with AI magic, real-time alerts, and more fun than a barrel of monkeys! 🐵🎉
> 
> 🎭 **Prepare to be amazed!** 🎭

---

## ✨ Features That Will Make You Go WOW! ✨

<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/212284087-bbe7e430-757e-4901-90bf-4cd2ce3e1852.gif" width="100">

</div>

| 🎭 **Feature** | 🎪 **Description** | 🎨 **Fun Factor** | 🚀 **Status** |
|:---:|:---:|:---:|:---:|
| 📸 **Face Detection** | InsightFace (buffalo_l) magic! | 🌟🌟🌟🌟🌟 | ![Active](https://img.shields.io/badge/Status-Active-brightgreen) |
| 🎛️ **Admin Dashboard** | Approve/ban users like a boss! | 🌟🌟🌟🌟 | ![Ready](https://img.shields.io/badge/Status-Ready-blue) |
| 📧📱 **Smart Alerts** | Email & SMS notifications! | 🌟🌟🌟 | ![Live](https://img.shields.io/badge/Status-Live-orange) |
| 🗄️ **Database Magic** | SQLite storage wizardry! | 🌟🌟🌟 | ![Stable](https://img.shields.io/badge/Status-Stable-success) |
| 🖼️ **Image Processing** | AI-powered preprocessing! | 🌟🌟 | ![Enhanced](https://img.shields.io/badge/Status-Enhanced-purple) |
| 🌐 **RESTful API** | Modern API goodness! | 🌟🌟🌟 | ![Optimized](https://img.shields.io/badge/Status-Optimized-yellow) |

<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="100">

</div>

---

## 🗂️ Project Structure 🏗️

<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/212284136-03988914-d42b-45cb-b001-c9c85524f92a.gif" width="150">

</div>

```bash
🎪 atm-security-system/
├── 🎭 app.py                    # Flask admin dashboard
├── 👁️ detect.py                 # Real-time detection & recognition
├── 📢 alerts.py                 # Send email & SMS alerts
├── 🖼️ preprocess.py              # Align & clean face images
├── 🧠 create_embeddings.py      # Generate ArcFace embeddings
├── 💾 embeddings.npz            # Saved 512D vectors of all users
├── 🗄️ face_auth.db              # SQLite DB for users & logs
│
├── 📁 dataset/
│   ├── ✅ authorized/<name>/    # Authorized face images
│   └── ❌ unauthorized/         # Unauthorized face attempts
│
├── 👥 authorized_faces/         # Approved images
├── 🚫 banned_faces/             # Disapproved images
├── ⚙️ processed_dataset/        # Preprocessed aligned images
├── 🐛 debug_failed_faces/       # Debugging false/failed faces
│
├── 🎨 templates/
│   ├── 🔐 login.html            # Admin login page
│   └── 📊 dashboard.html        # Admin control panel
│
├── 💄 static/
│   ├── 🎨 style.css             # Dark mode CSS
│   └── ⚡ dashboard.js          # UI interactivity
│
├── 🔑 .env                      # Email/Twilio credentials
├── 📋 requirements.txt          # All required packages
└── 📖 README.md                 # This magical file
```

---

## 🛠️ Prerequisites (Your Superhero Toolkit!) 🛠️

<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/212284094-e50ceae2-de86-4dd6-b97c-3b5a0dd78bb5.gif" width="200">

</div>

<table align="center">
<tr>
<td align="center" width="20%">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="60" height="60"><br>
<b>🐍 Python 3.8+</b><br>
<sub>The snake that runs it all!</sub>
</td>
<td align="center" width="20%">
<img src="https://images.unsplash.com/photo-1485827404703-89b55fcc595e?w=60&h=60&fit=crop&crop=center" width="60" height="60" style="border-radius: 8px;"><br>
<b>📷 Webcam/Camera</b><br>
<sub>Your window to faces!</sub>
</td>
<td align="center" width="20%">
<img src="https://avatars.githubusercontent.com/u/109142?s=60&v=4" width="60" height="60" style="border-radius: 8px;"><br>
<b>📱 Twilio Account</b><br>
<sub>Your SMS superhero!</sub>
</td>
<td align="center" width="20%">
<img src="https://developers.google.com/gmail/images/gmail_lockup_color_1x_web_64dp.png" width="60" height="60"><br>
<b>📧 Gmail SMTP</b><br>
<sub>Your email wizard!</sub>
</td>
<td align="center" width="20%">
<img src="https://raw.githubusercontent.com/opencv/opencv/master/doc/opencv-logo.png" width="60" height="60"><br>
<b>🎥 OpenCV</b><br>
<sub>Computer vision magic!</sub>
</td>
</tr>
</table>

---

## ⚙️ Installation (The Fun Setup Adventure!) ⚙️

<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/212284145-bf2c01a8-c448-4f1a-b911-996024c84606.gif" width="200">

</div>

### 🎯 **Step-by-Step Magic Setup** 🎯

```bash
# 🎪 Step 1: Clone the magical repo
git clone https://github.com/sagnik7081/SentinelVaultX
cd Enhanced-Atm-Security

# 🐍 Step 2: Create your Python playground
python -m venv venv
venv\Scripts\activate       # 🪟 On Windows
source venv/bin/activate    # 🐧 On Linux/Mac

# 📦 Step 3: Install the magic potions
pip install -r requirements.txt

# 🔑 Step 4: Configure your secret powers (edit `.env`)
EMAIL_SENDER=your-email@gmail.com
EMAIL_PASSWORD=your-app-password
TWILIO_ACCOUNT_SID=xxxx
TWILIO_AUTH_TOKEN=xxxx
TWILIO_PHONE_NUMBER=+1234567890

# 🖼️ Step 5: Prepare the AI brain
python preprocess.py
python create_embeddings.py

# 🚀 Step 6: Launch the security carnival!
python app.py      # 🎛️ Run Flask dashboard
python detect.py   # 👁️ Start real-time face detection
```

<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/212284119-fbfd994d-8c2a-4c3d-9f9b-9f8b8c0e1e1a.gif" width="100">

**🎉 BOOM! Your security system is now ALIVE! 🎉**

</div>

---

## 🎭 How It Works (The Magic Behind The Curtain) 🎭

<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="600">

</div>

### 🔄 **The Security Dance** 🔄

1. 📸 **Camera captures face** → 🎭 **AI detects features**
2. 🧠 **Creates 512D embedding** → 🔍 **Compares with database**
3. ✅ **Match found?** → 🎉 **Welcome!** | ❌ **No match?** → 🚨 **ALERT!**
4. 📱 **SMS sent** → 📧 **Email dispatched** → 📊 **Dashboard updated**

---

## 🎨 Tech Stack (The Superhero Squad) 🦸‍♂️

<div align="center">

<table>
<tr>
<td align="center" width="16.66%">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="60" height="60"><br>
<b>Python</b><br>
<sub>🐍 Core Logic</sub>
</td>
<td align="center" width="16.66%">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flask/flask-original.svg" width="60" height="60"><br>
<b>Flask</b><br>
<sub>🌐 Web Framework</sub>
</td>
<td align="center" width="16.66%">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/opencv/opencv-original.svg" width="60" height="60"><br>
<b>OpenCV</b><br>
<sub>👁️ Computer Vision</sub>
</td>
<td align="center" width="16.66%">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sqlite/sqlite-original.svg" width="60" height="60"><br>
<b>SQLite</b><br>
<sub>🗄️ Database</sub>
</td>
<td align="center" width="16.66%">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" width="60" height="60"><br>
<b>HTML5</b><br>
<sub>🎨 Frontend</sub>
</td>
<td align="center" width="16.66%">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="60" height="60"><br>
<b>JavaScript</b><br>
<sub>⚡ Interactivity</sub>
</td>
</tr>
</table>

### 🎯 **Power Categories**

<table>
<tr>
<td width="33%" align="center">

**🤖 AI & Recognition**
- InsightFace (Buffalo_L)
- ArcFace Embeddings
- Face Alignment
- Feature Extraction

</td>
<td width="33%" align="center">

**🌐 Web & Backend**
- Flask Web Framework
- SQLite Database
- RESTful API
- Session Management

</td>
<td width="33%" align="center">

**📱 Communication**
- Twilio SMS API
- Gmail SMTP
- Real-time Alerts
- Dashboard Notifications

</td>
</tr>
</table>

</div>

---

## 👥 Meet The Dream Team! 🌟

<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="300">

<table>
<tr>
<td align="center" width="50%">
<a href="https://github.com/sagnik7081">
<img src="https://avatars.githubusercontent.com/u/108155574?v=4" width="150px;" alt="Sagnik" style="border-radius: 50%; border: 4px solid #FF6B35;"/><br />
<sub><b>Sagnik7081</b></sub><br />
</a>
</td>
<td align="center" width="50%">
<a href="https://github.com/Shaurya-2004">
<img src="https://avatars.githubusercontent.com/u/108155574?v=4" width="150px;" alt="Sagnik" style="border-radius: 50%; border: 4px solid #FF6B35;"/><br />
<sub><b>Shaurya-2004</b></sub><br />
</a>
</td>
</tr>
</table>

<p>
<img src="https://img.shields.io/badge/Team-2%20Developers-blue?style=for-the-badge&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/Contributions-Welcome-brightgreen?style=for-the-badge&logo=git&logoColor=white">
<img src="https://img.shields.io/badge/Fun%20Level-Maximum-ff69b4?style=for-the-badge&logo=smile&logoColor=white">
</p>

### 🎪 **Join Our Circus!** 🎪

Want to be part of this amazing security carnival? We'd love to have you aboard! 🎠

</div>


---

## 🚀 What's Next? (Future Magic!) 🔮

<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/212284126-aa4e8b6e-7b6b-4f85-8d1b-4e6d6c5c5c5c.gif" width="150">

</div>

- 🎭 **Multi-face recognition** for group authentication
- 🌈 **Rainbow dashboard themes** for extra fun
- 🎵 **Sound alerts** with custom notification tones
- 📊 **Advanced analytics** with beautiful charts
- 🌍 **Multi-language support** for global security
- 🎮 **Gamification** with security achievement badges

---

<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">

### 🎪 **Thank You For Visiting Our Security Carnival!** 🎪

<img src="https://forthebadge.com/images/badges/built-with-love.svg" alt="Built with Love">
<img src="https://forthebadge.com/images/badges/powered-by-coffee.svg" alt="Powered by Coffee">
<img src="https://forthebadge.com/images/badges/makes-people-smile.svg" alt="Makes People Smile">

**⭐ Don't forget to star this repo if it made you smile! ⭐**

<img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="200">

### 🎉 Happy Securing! May Your ATMs Be Forever Protected! 🎉

</div>
