# 🎥 HLS / DASH / MP4 Player

A lightweight web-based video player that supports **HLS**, **DASH**, **M3U**, **M3U8**, and **MP4** streaming formats.  
Built with a clean UI, custom URL input, and automatic quality switching.

---

## 🚀 Features

- ▶️ Play **HLS (.m3u8)** streams  
- 🎞️ Play **DASH (.mpd)** streams  
- 📁 Supports **MP4** direct URLs  
- 📶 Auto quality detection  
- 🖥️ Full-screen mode  
- 🔊 Volume control  
- 🏃 Playback speed control  
- ⛔ Developer tools restricted (anti-tampering protection)  
- 🔐 Scripts are **obfuscated** for enhanced security  

---

## 🌐 Live Demo

🔗 **https://hls-brown.vercel.app**

---

## 📸 Screenshot

*(Replace with your actual screenshot)*  
![Player Screenshot](./screenshot.png)

---

## 🔧 Usage

1. Open the player in your browser.
2. Enter a valid streaming URL:
   - HLS: `https://example.com/stream.m3u8`
   - DASH: `https://example.com/manifest.mpd`
   - MP4: `https://example.com/video.mp4`
3. Click **LOAD**.
4. Enjoy smooth playback with automatic resolution adjustments.

---

## 📁 Supported Formats

| Type | Extension |
|------|-----------|
| HLS | `.m3u8`, `.m3u` |
| DASH | `.mpd` |
| MP4 | `.mp4` |

---

## 🛡️ Security Notes

- Developer Tools are restricted to prevent tampering.
- Core JavaScript is intentionally **obfuscated**.
- No analytics or tracking scripts are included.

---

## 📦 Deployment

This site is deployed on **Vercel**.

To deploy your own version:

```sh
git clone https://github.com/YOUR-USERNAME/REPO-NAME.git
cd REPO-NAME
npm install
vercel deploy
