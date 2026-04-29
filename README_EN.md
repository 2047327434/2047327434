<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=soft&color=0:f8fafc,100:e2e8f0&height=140&section=header&text=YHome&fontSize=52&fontColor=0284c7&fontAlignY=50&desc=Neijiang%2C%20China%20%C2%B7%20transcosmos&descSize=14&descAlignY=72&descColor=64748b" />

[![Home](https://img.shields.io/badge/YHome-yuhanghome.icu-0284c7?style=flat-square&labelColor=e2e8f0)](https://yuhanghome.icu)
[![Radio](https://img.shields.io/badge/FM-fm.yuhanghome.icu-7c3aed?style=flat-square&labelColor=e2e8f0)](https://fm.yuhanghome.icu)
[![GitHub](https://img.shields.io/badge/GitHub-2047327434-475569?style=flat-square&logo=github&logoColor=white&labelColor=e2e8f0)](https://github.com/2047327434)
[![中文](https://img.shields.io/badge/🌐_中文-点击切换-0284c7?style=flat-square&labelColor=e2e8f0)](https://github.com/2047327434/2047327434)

</div>

---

> 📍 **Neijiang, China** · 🏢 **transcosmos** · 💡 *Ship it, then iterate.*
>
> 🛠 Python · FastAPI · WebSocket · JavaScript · Docker · Nginx · Glassmorphism UI

---

### 🗂️ Projects

<div align="center">
  <a href="https://github.com/2047327434/music-radio">
    <img align="center" height="150" src="https://github-readme-stats.vercel.app/api/pin/?username=2047327434&repo=music-radio&theme=blue-green&hide_border=true&bg_color=f8fafc&title_color=0284c7&icon_color=0284c7&text_color=475569" />
  </a>
  <a href="https://github.com/2047327434/SyncCinema">
    <img align="center" height="150" src="https://github-readme-stats.vercel.app/api/pin/?username=2047327434&repo=SyncCinema&theme=blue-green&hide_border=true&bg_color=f8fafc&title_color=0284c7&icon_color=0284c7&text_color=475569" />
  </a>
</div>
<div align="center">
  <a href="https://github.com/2047327434/YXT-auto-study-helper">
    <img align="center" height="150" src="https://github-readme-stats.vercel.app/api/pin/?username=2047327434&repo=YXT-auto-study-helper&theme=blue-green&hide_border=true&bg_color=f8fafc&title_color=0284c7&icon_color=0284c7&text_color=475569" />
  </a>
  <a href="https://github.com/2047327434/what-am-i-doing">
    <img align="center" height="150" src="https://github-readme-stats.vercel.app/api/pin/?username=2047327434&repo=what-am-i-doing&theme=blue-green&hide_border=true&bg_color=f8fafc&title_color=0284c7&icon_color=0284c7&text_color=475569" />
  </a>
</div>

<details>
<summary><b>🎧 Music Radio</b> — Real-time Radio · Server-driven Playback · Unified Track Abstraction</summary>
<br>

`FastAPI` `WebSocket` `HTTP Range` `Mutagen`

Online music radio with DJ console + synchronized listeners + live chat

- 🎛️ DJ Console — playback control, drag-sort playlist, listener management, kick
- 🔄 Server-driven loop — auto next-track 0.5s before song ends, plays on even if DJ leaves
- 📡 WebSocket broadcast — state changes pushed instantly, zero-delay sync for listeners
- 🎵 Three sources unified — upload files / URL add / local directory, all as track objects
- 📊 HTTP Range streaming — play-while-downloading + seek, auto 302 redirect for URLs
- 🎤 Multi-source lyrics — LRCLIB exact/fuzzy + NetEase Cloud, covering EN/CN/JP lyrics
- 🖼️ Cover auto-extraction — mutagen parses embedded covers from MP3/M4A/FLAC/OGG/WMA
- 🛡️ Security — path traversal prevention + Admin SHA-256 auth + Token mechanism
- 🌙 Apple Music Night dark theme + Glassmorphism UI + mobile responsive
- 📡 20+ API endpoints, single-file SPA architecture

🌐 [Live Demo](https://fm.yuhanghome.icu) · 📦 [Source](https://github.com/2047327434/music-radio)

</details>

<details>
<summary><b>🎬 SyncCinema</b> — Sync Watch · Danmaku · WebRTC Voice</summary>
<br>

`Express` `Socket.io` `WebRTC` `JWT` `bcrypt`

Real-time synchronized watching web app — watch together from anywhere

- 🎬 Millisecond sync — play/pause/seek/speed all synced across room in real-time
- 💬 Live chat + Danmaku — scroll/top/bottom modes, keyword filtering support
- 📹 Multi-source video — MP4/WebM/OGG/HLS(m3u8) + YouTube/Bilibili iframe embed
- 🎤 WebRTC P2P voice chat — in-room voice calls (experimental)
- 🖥️ Screen sharing — host's screen broadcasted to entire room
- 🔒 Room management — public/private rooms, password protection, auto host transfer
- 📋 Playlist — multi-video auto-play, prev/next switch
- ⏰ Auto-off timer + 45-min break reminders
- 🛡️ Full security hardening — XSS/onclick/IDOR/Rate Limiting/JWT auth all patched
- 👤 User system — register/login, avatar, signature, admin role, ban mechanism
- 📱 Dark theme + responsive + admin dashboard (users/rooms/stats)

📦 [Source](https://github.com/2047327434/SyncCinema)

</details>

<details>
<summary><b>📚 YXT Auto Study Helper</b> — Auto Study · Anti-detection · Chrome Extension</summary>
<br>

`JavaScript` `Chrome Extension API` `WebSocket`

Chrome extension for YunXueTang auto-study with anti-detection mechanisms

- ▶️ Auto-play — detects and plays video on page load, no manual click needed
- ⏭️ Auto-next — automatically clicks "next" when video ends, seamless course switch
- 🔇 Background silent — auto-mute, video plays in background without disturbance
- 🛡️ Focus keep-alive — overrides visibilitychange, tab switch won't pause video
- 🎭 Anti-detection — 5% chance of 1~3s pause every 30~60s, simulating real user behavior
- ❌ Smart popup close — auto-closes notification popups, preserves exam/quiz/assessment popups
- 📊 Real-time stats — runtime, completed courses, current video progress
- 🔄 State persistence — chrome.storage saves state, auto-resumes after page refresh

📦 [Source](https://github.com/2047327434/YXT-auto-study-helper)

</details>

<details>
<summary><b>🤔 What Am I Doing</b> — Real-time Status · Glassmorphism · System Tray</summary>
<br>

`FastAPI` `WebSocket` `Python ctypes` `pystray` `SQLite`

Lightweight tool that displays your PC usage status in real-time

- 🖥️ Real-time status — shows current app name and window title
- ⏱️ Usage duration — today's cumulative usage, auto-detects active/idle
- 📊 App ranking — ranked by usage time, precise to seconds
- 💬 Live chat — bidirectional chat between visitors and admin
- 🔔 Toast notifications — visitor messages trigger Windows Toast notifications
- 🟢 System tray — no console window, runs silently in system tray
- 🧠 Smart capture — Windows ctypes API fetches foreground window info
- 🪟 Glassmorphism UI — iOS-style frosted glass interface
- 💾 SQLite async persistence — messages and states persist

📦 [Source](https://github.com/2047327434/what-am-i-doing)

</details>

---

### 🖥️ Server Status

<div align="center">

![Uptime](https://img.shields.io/badge/Uptime-Running-16a34a?style=flat-square&labelColor=e2e8f0&logo=server&logoColor=16a34a)
![Services](https://img.shields.io/badge/Services-6+-0284c7?style=flat-square&labelColor=e2e8f0&logo=docker&logoColor=0284c7)
![Stack](https://img.shields.io/badge/Stack-FastAPI-7c3aed?style=flat-square&labelColor=e2e8f0&logo=python&logoColor=7c3aed)
![Domain](https://img.shields.io/badge/Domain-yuhanghome.icu-db2777?style=flat-square&labelColor=e2e8f0&logo=globe&logoColor=db2777)

</div>

---

### 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white&labelColor=e2e8f0)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white&labelColor=e2e8f0)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socket.io&logoColor=white&labelColor=e2e8f0)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white&labelColor=e2e8f0)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white&labelColor=e2e8f0)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black&labelColor=e2e8f0)
![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white&labelColor=e2e8f0)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white&labelColor=e2e8f0)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white&labelColor=e2e8f0)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white&labelColor=e2e8f0)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white&labelColor=e2e8f0)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black&labelColor=e2e8f0)

</div>

---

### 📊 Stats

<div align="center">
  <img height="155" src="https://github-readme-stats.vercel.app/api?username=2047327434&show_icons=true&theme=default&hide_border=true&bg_color=f8fafc&title_color=0284c7&icon_color=0284c7&text_color=475569&ring_color=0284c7" />
  <img height="155" src="https://github-readme-stats.vercel.app/api/top-langs/?username=2047327434&layout=compact&theme=default&hide_border=true&bg_color=f8fafc&title_color=0284c7&text_color=475569" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=2047327434&theme=default&hide_border=true&background=F8FAFC&ring=0284C7&fire=0284C7&currStreakLabel=0284C7&sideLabels=475569&dates=475569" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=2047327434&bg_color=f8fafc&color=0284c7&line=0284c7&point=0f172a&area=true&hide_border=true" />
</div>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=2047327434&color=0284c7&style=flat-square&label=visitors" />
</div>

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=soft&color=0:e2e8f0,100:f8fafc&height=40&section=footer" />
</div>
