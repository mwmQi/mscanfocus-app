# 🔺 mScanFocus - Advanced HTTP Scanner for Android

<p align="center">
  <strong>Fast • Powerful • Secure</strong><br/>
  <em>Batch scan hosts, extract results, and upload to Telegram</em>
</p>

<p align="center">
  <a href="#-features">Features</a> •
  <a href="#-download">Download</a> •
  <a href="#-how-to-use">How to Use</a> •
  <a href="#-screenshots">Screenshots</a> •
  <a href="#-faq">FAQ</a>
</p>

---

## ⚡ Features

| Feature | Description |
|---------|-------------|
| **🚀 Fast Scanning** | Multi-threaded HTTP scanning with configurable threads (default: 50) |
| **📁 Batch Processing** | Scan hundreds of hosts from a single `.txt` file |
| **🌐 Multiple Methods** | Support for HEAD, GET, POST, PUT, DELETE HTTP methods |
| **📤 Telegram Upload** | Send scan results directly to your Telegram bot |
| **🛠️ Toolkit** | Deduplicate, clean, extract domains/IPs, split large files |
| **💾 Auto-Resume** | Resume interrupted scans automatically |
| **⏸️ Pause/Resume** | Pause active scans and continue later |
| **📊 Live Stats** | Real-time progress, speed (h/s), and hit counter |
| **🌙 Dark Theme** | Beautiful black/violet/green UI optimized for night use |

---

## 📥 Download

**Latest Version:** `v1.0` (Debug Build)

📦 **[Download APK](https://github.com/mwmQi/mscanfocus-app/releases/download/v1.0/app-debug.apk)**

### Installation
1. Download the APK above
2. Enable **"Install from Unknown Sources"** in Android settings
3. Open the APK and install
4. Grant storage permissions when prompted

> **⚠️ Note:** This is a debug build. For production releases, check the [Releases](https://github.com/mwmQi/mscanfocus-app/releases) page.

---

## 📋 Requirements

- **Android Version:** 7.0+ (API 24)
- **Permissions Required:**
  - `INTERNET` - For HTTP scanning
  - `MANAGE_EXTERNAL_STORAGE` - To read/write scan files
  - `FOREGROUND_SERVICE` - To run scans in background
  - `POST_NOTIFICATIONS` - For scan notifications
  - `WAKE_LOCK` - To keep CPU awake during scans

---

## 📖 How to Use

### 1️⃣ Prepare Input Files

Create a `.txt` file with **one host per line**:

```
example.com
192.168.1.1
test.site.org
api.example.net
```

Place the file in:
```
/storage/emulated/0/download/🔺mscanfocus🔺/🔍manual_scan/
```

### 2️⃣ Start Scanning

1. Open the app
2. Tap **SCAN FILE**
3. Select your `.txt` file
4. Watch live results in the scan screen!

### 3️⃣ View Results

- Results saved to: `/storage/emulated/0/download/🔺mscanfocus🔺/🔍manual_scan/📁xresult_manual/`
- Scanned files moved to: `/storage/emulated/0/download/🔺mscanfocus🔺/🔍manual_scan/scanned_txt's/`
- View all history in **HISTORY** tab

### 4️⃣ Configure Settings

Go to **SETTINGS** to customize:
- **Ports:** `443,80,8080` (comma-separated)
- **Threads:** `50` (recommended), up to `200+` for aggressive scanning
- **Timeout:** `3` seconds (default)
- **HTTP Method:** `HEAD` (fastest), `GET`, `POST`, `PUT`, `DELETE`
- **Skip 302:** Filter redirect responses

### 5️⃣ Upload to Telegram

1. Go to **SETTINGS**
2. Configure:
   - **Bot Token:** Get from [@BotFather](https://t.me/BotFather)
   - **Chat ID:** Get from [@userinfobot](https://t.me/userinfobot)
3. Go to **HISTORY** → Tap **Upload** on any result

### 6️⃣ Use Toolkit

Go to **TOOLKIT** for file utilities:
- **Deduplicate** - Remove duplicate lines & sort
- **Clean & Extract** - Extract domains and IPs into separate files
- **Split Archive** - Divide large files into parts

---

## 📸 Screenshots

| Dashboard | Active Scan | History |
|-----------|-------------|---------|
| ![Dashboard](screenshots/dashboard.png) | ![Scan](screenshots/scan.png) | ![History](screenshots/history.png) |

> *Screenshots coming soon!*

---

## 📁 File Structure

```
📂 /storage/emulated/0/download/🔺mscanfocus🔺/
├── 📂 🔍manual_scan/
│   ├── 📄 your_input_file.txt          ← Place input files here
│   ├── 📂 📁xresult_manual/            ← Scan results saved here
│   └── 📂 scanned_txt's/               ← Scanned files moved here
└── 📂 🔧settings/
    └── settings.json                   ← App settings
```

---

## ❓ FAQ

**Q: Why is scanning slow?**  
A: Reduce thread count to 30-50. Use HEAD method. Check network stability.

**Q: No results found?**  
A: Verify hosts are valid. Check timeout setting. Try different ports.

**Q: App crashed, lost progress?**  
A: Progress is auto-saved! Reopen app and tap "Resume".

**Q: Telegram upload fails?**  
A: Verify bot token and chat ID are correct. Ensure bot is not blocked.

**Q: Where are my files?**  
A: Check `/storage/emulated/0/download/🔺mscanfocus🔺/` folders.

---

## ⚠️ Disclaimer

This tool is for **educational and authorized testing purposes only**. 

- Only scan servers you own or have permission to test
- Do not use for malicious activities
- High thread counts may trigger rate limiting or IP bans
- Use responsibly!

---

## 🛠️ Built With

- **Kotlin** - 100% Kotlin codebase
- **Jetpack Compose** - Modern UI
- **OkHttp** - HTTP client
- **Coroutines** - Async operations
- **MVVM Architecture** - Clean architecture

---

## 📝 License

This project is provided as-is for educational purposes.

---

## 🤝 Contributing

Found a bug? Have a feature request?  
📧 Open an [Issue](https://github.com/mwmQi/mscanfocus-app/issues)

---

<p align="center">
  <strong>Made with ❤️ for the Android security community</strong><br/>
  <em>⭐ Star this repo if you find it useful!</em>
</p>
