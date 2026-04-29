<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=soft&color=0:f8fafc,100:e2e8f0&height=140&section=header&text=YHome&fontSize=52&fontColor=0284c7&fontAlignY=50&desc=Neijiang%2C%20China%20%C2%B7%20transcosmos&descSize=14&descAlignY=72&descColor=64748b" />

[![Home](https://img.shields.io/badge/YHome-yuhanghome.icu-0284c7?style=flat-square&labelColor=e2e8f0)](https://yuhanghome.icu)
[![Radio](https://img.shields.io/badge/FM-fm.yuhanghome.icu-7c3aed?style=flat-square&labelColor=e2e8f0)](https://fm.yuhanghome.icu)
[![GitHub](https://img.shields.io/badge/GitHub-2047327434-475569?style=flat-square&logo=github&logoColor=white&labelColor=e2e8f0)](https://github.com/2047327434)
[![English](https://img.shields.io/badge/🌐_English-Click_here-0284c7?style=flat-square&labelColor=e2e8f0)](https://github.com/2047327434/2047327434/blob/main/README_EN.md)

</div>

---

> 📍 **内江, 中国** · 🏢 **transcosmos** · 💡 *做出来，再迭代*
>
> 🛠 Python · FastAPI · WebSocket · JavaScript · Docker · Nginx · Glassmorphism UI

---

### 🗂️ 项目

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
<summary><b>🎧 Music Radio</b> — 实时音乐电台 · 服务端驱动播放 · 三源统一抽象</summary>
<br>

`FastAPI` `WebSocket` `HTTP Range` `Mutagen`

DJ 控制台 + 听众端同步收听 + 实时聊天的在线音乐电台

- 🎛️ DJ 控制台：播放控制、播放列表拖拽排序、在线听众管理、踢人
- 🔄 服务端驱动循环播放 — 歌曲结束前 0.5s 自动切歌，DJ 关页面音乐不停
- 📡 WebSocket 广播同步 — 状态变更即推送，听众零延迟跟随
- 🎵 三种音源统一抽象 — 上传文件 / URL 添加 / 本地目录浏览，统一为 track 对象
- 📊 HTTP Range 流式传输 — 边下边播 + seek，URL 类型自动 302 重定向
- 🎤 多源歌词搜索 — LRCLIB 精确/模糊 + 网易云，覆盖中英日歌词
- 🖼️ 封面自动提取 — mutagen 解析 MP3/M4A/FLAC/OGG/WMA 内嵌封面
- 🛡️ 安全设计 — 本地路径防遍历 + Admin SHA-256 哈希认证 + Token 机制
- 🌙 Apple Music Night 深色主题 + 玻璃态 UI + 移动端适配
- 📡 20+ API 端点，单文件 SPA 架构

🌐 [在线体验](https://fm.yuhanghome.icu) · 📦 [源码](https://github.com/2047327434/music-radio)

</details>

<details>
<summary><b>🎬 SyncCinema</b> — 同步观影 · 弹幕系统 · WebRTC 语音</summary>
<br>

`Express` `Socket.io` `WebRTC` `JWT` `bcrypt`

多人实时同步观影 Web 应用，让远方的朋友一起看片

- 🎬 毫秒级同步 — 播放/暂停/进度跳转/倍速全房间实时同步
- 💬 实时聊天 + 弹幕系统 — 滚动/顶部/底部三种弹幕模式，支持关键词屏蔽
- 📹 多源视频 — MP4/WebM/OGG/HLS(m3u8) + YouTube/Bilibili iframe 嵌入
- 🎤 WebRTC P2P 语音聊天 — 房内语音通话（实验性）
- 🖥️ 屏幕实时分享 — 房主屏幕广播给全房间
- 🔒 房间管理 — 公开/私密房间、密码保护、房主离开自动转让
- 📋 播放列表 — 多视频自动连续播放，支持上下切换
- ⏰ 定时关闭 + 每 45 分钟休息提醒
- 🛡️ 完整安全加固 — XSS/onclick/IDOR/Rate Limiting/JWT 认证全修复
- 👤 用户系统 — 注册登录、头像、签名、管理员角色、封禁机制
- 📱 暗黑主题 + 响应式 + 管理后台（用户/房间/统计）

📦 [源码](https://github.com/2047327434/SyncCinema)

</details>

<details>
<summary><b>📚 YXT Auto Study Helper</b> — 云学堂挂课 · 反检测模拟 · Chrome 插件</summary>
<br>

`JavaScript` `Chrome Extension API` `WebSocket`

专为云学堂设计的 Chrome 浏览器插件，自动挂课 + 防检测

- ▶️ 自动播放 — 页面加载后自动检测视频并播放，无需手动
- ⏭️ 自动切课 — 视频播完自动点击「下一个」，无缝切换
- 🔇 后台静默 — 自动静音，视频后台播放不干扰其他操作
- 🛡️ 失焦保活 — 覆盖 visibilitychange 事件，标签页切换不暂停
- 🎭 反检测模拟 — 每 30~60s 有 5% 概率暂停 1~3s，模拟真实用户偶尔离开
- ❌ 弹窗自动关闭 — 自动关闭提示弹窗，保留考试/练习/测评关键弹窗
- 📊 实时统计 — 运行时长、已完成课程数、当前视频进度
- 🔄 状态持久化 — chrome.storage 保存状态，页面刷新自动恢复

📦 [源码](https://github.com/2047327434/YXT-auto-study-helper)

</details>

<details>
<summary><b>🤔 What Am I Doing</b> — 实时状态展示 · 玻璃态 UI · 托盘常驻</summary>
<br>

`FastAPI` `WebSocket` `Python ctypes` `pystray` `SQLite`

实时展示电脑使用状态的轻量工具，让访客知道你正在做什么

- 🖥️ 实时状态 — 显示当前使用的应用名称和窗口标题
- ⏱️ 使用时长 — 今日累计使用时长，自动区分活跃/空闲
- 📊 应用排行 — 按使用时长排序的应用排行，精确到分秒
- 💬 实时聊天 — 访客与 Admin 双向聊天
- 🔔 消息通知 — 访客消息自动弹 Windows Toast 通知
- 🟢 托盘常驻 — 无控制台窗口，系统托盘后台静默运行
- 🧠 智能采集 — Windows ctypes API 获取前台窗口信息
- 🪟 玻璃态 UI — iOS 风格毛玻璃界面
- 💾 SQLite 异步持久化 — 消息和状态可持久保留

📦 [源码](https://github.com/2047327434/what-am-i-doing)

</details>

---

### 🖥️ 服务状态

<div align="center">

![Uptime](https://img.shields.io/badge/运行中-Running-16a34a?style=flat-square&labelColor=e2e8f0&logo=server&logoColor=16a34a)
![Services](https://img.shields.io/badge/服务-6+-0284c7?style=flat-square&labelColor=e2e8f0&logo=docker&logoColor=0284c7)
![Stack](https://img.shields.io/badge/架构-FastAPI-7c3aed?style=flat-square&labelColor=e2e8f0&logo=python&logoColor=7c3aed)
![Domain](https://img.shields.io/badge/域名-yuhanghome.icu-db2777?style=flat-square&labelColor=e2e8f0&logo=globe&logoColor=db2777)

</div>

---

### 🛠️ 技术栈

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

### 📊 数据

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
