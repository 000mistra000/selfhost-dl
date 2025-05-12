<div align='center'>

<br />
<div align="center">
  <a href="https://files.catbox.moe/6xogr9.svg">
    <img src="https://files.catbox.moe/6xogr9.svg" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">selfhost-dl</h3>

  <p align="center">
    <strong>SelfHost-DL is my project that lets users self-host a simple web downloader with minimal setup. Just run it with Node.js—no third-party services needed. Deploy the files, start the server, and download content easily. Perfect for a lightweight, self-managed solution..</strong>
  </p>
</div>



<div align='center'>

![GitHub Repo stars](https://img.shields.io/github/stars/000mistra000/selfhost-dl?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/000mistra000/selfhost-dl?style=for-the-badge)
![GitHub watchers](https://img.shields.io/github/watchers/000mistra000/selfhost-dl?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/000mistra000/selfhost-dl?style=for-the-badge)
![GitHub license](https://img.shields.io/github/license/000mistra000/selfhost-dl?style=for-the-badge)

---------------
### **THIS CODE IS FOR EDUCATIONAL PURPOSES ONLY, USE IT WISELY, ANY MISUSE IS NOT THE RESPONSIBILITY OF THE CREATOR.**  

# SCREENSHOT

</div>

<p align="center">
  <a href="https://ibb.co/j9scmGHy">
    <img src="https://i.ibb.co/HL3W6YXt/Screenshot-2025-02-16-120806.png" alt="Screenshot-2025-02-16-120806" border="0">
  </a>
  <a href="https://ibb.co/5XWt9LcD">
    <img src="https://i.ibb.co/PsZ3YgCp/Screenshot-2025-02-16-120812.png" alt="Screenshot-2025-02-16-120812" border="0">
  </a>
  <a href="https://ibb.co/ZRjYJPsg">
    <img src="https://i.ibb.co/5X0n9yDj/Screenshot-2025-02-16-120836.png" alt="Screenshot-2025-02-16-120836" border="0">
  </a>
</p>
</div>

---------------

## 🚀 Features
- **Scrape APIs** – Uses various APIs to fetch and download media.  
- **Requires Only Node.js** – No database or heavy dependencies needed.  
- **Lightweight & Fast** – Optimized for speed and minimal resource usage.  
- **Supports multiple platforms:**
  - **TikTok**: `TiktokDownloader`
  - **CapCut**: `CapcutDownloader`
  - **Xiaohongshu**: `XiaohongshuDownloader`
  - **Threads**: `ThreadsDownloader`
  - **SoundCloud**: `SoundcloudDownloader`
  - **Spotify**: `SpotifyDownloader`
  - **Instagram**: `InstagramDownloader`
  - **Facebook**: `FacebookDownloader`
  - **Terabox**: `TeraboxDownloader`
  - **SnackVideo**: `SnackVideoDownloader`
- **Easy to Use** – Simple setup and intuitive usage.  
- **Vercel Deployment Support** – Deploy in seconds with a single click.  

---------------
## This project can be run in three ways:
1. **Locally** (on your machine)
2. **On a VPS** (self-hosted)
3. **Deploying to Vercel** (serverless)

---

## 🖥️ Running Locally

1. **Clone the repository:**
   ```sh
   git clone https://github.com/000mistra000/selfhost-dl.git
   cd selfhost-dl
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Start the server:**
   ```sh
   node index.js
   ```

4. **Access the app:**
   ```
   http://localhost:<PORT>
   ```

---

## 🌍 Running on a VPS

### Prerequisites:
- A VPS with **Node.js (v16+)** installed
- **PM2** (for process management)

1. **Connect to your VPS** via SSH:
   ```sh
   ssh user@your-vps-ip
   ```

2. **Clone the repository:**
   ```sh
   git clone https://github.com/000mistra000/selfhost-dl.git
   cd selfhost-dl
   ```

3. **Install dependencies:**
   ```sh
   npm install
   ```

4. **Run with PM2 (recommended for production):**
   ```sh
   npm install -g pm2
   pm2 start index.js --name selfhost-dl
   pm2 save
   pm2 startup
   ```

5. **Access the app via your VPS IP:**
   ```
   http://your-vps-ip:<PORT>
   ```

(Optional) **Use Nginx as a reverse proxy** for a custom domain and SSL setup.

---

## ☁️ Deploying to Vercel

### **One-Click Deploy**
Click the button below to instantly deploy to **Vercel**:

<p align="center">
  <a href="https://vercel.com/new/clone?repository-url=https://github.com/000mistra000/selfhost-dl">
    <img src="https://vercel.com/button" alt="Deploy to Vercel"/>
  </a>
</p>

---
## License
This project is licensed under the MIT License
