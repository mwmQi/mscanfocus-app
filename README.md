<p align="center">
  <img src="https://img.shields.io/badge/mScanFocus-Pro_Edition-7B2CBF?style=for-the-badge&logo=android&logoColor=white" alt="mScanFocus Pro">
  <br>
  <img src="https://img.shields.io/badge/High_Fidelity_Engine-Enabled-00FF88?style=flat-square" alt="High Fidelity Engine">
  <img src="https://img.shields.io/badge/Secure_Log_Export-Verified-white?style=flat-square" alt="Secure">
</p>

<h1 align="center">mScanFocus</h1>

<p align="center">
  <b>The Elite Network Discovery & HTTP Analysis Suite for Android</b><br>
  Designed for speed. Optimized for precision. Built for professionals.
</p>

<p align="center">
  <a href="https://github.com/mwmQi/mscanfocus-app/releases/download/v1.0/mScanFocus-Pro-v1.0.apk">
    <img src="https://img.shields.io/badge/DOWNLOAD-PRO_APK-00FF88?style=for-the-badge&logo=android&logoColor=black" alt="Download APK">
  </a>
</p>

<p align="center">
  <a href="#-technology">Technology</a> •
  <a href="#-gallery">Gallery</a> •
  <a href="#-deployment">Deployment</a> •
  <a href="#-requirements">Requirements</a> •
  <a href="https://t.me/mscanfocus">Support</a>
</p>

---

## 💎 The Gold Standard in Mobile Scanning

mScanFocus is not just a tool; it is a high-performance scanning ecosystem. By combining our proprietary high-velocity scanning core with advanced protocol validation, we provide a scanning experience previously only possible on desktop environments.

### 🚀 Advanced Scanning Engine
Our engine is optimized for complex protocol analysis. Built for absolute accuracy and deep response inspection, it ensures reliable data extraction across any network environment.

*   **🌙 AFK Stealth Mode:** Specialized power-saving layer for long-duration sessions. Implements an ultra-low brightness overlay with touch-locking to prevent accidental input while maintaining full core velocity.
*   **🎯 Intelligent Redirection Logic (302):** Automate your workflow with selective 302 handling. Filter out ISP recharge portals while preserving valid hits.

---

## 📸 Pro Gallery

<table align="center">
  <tr>
    <td width="33%"><img src="assets/screenshots/01_main_menu.png" alt="Command Center"></td>
    <td width="33%"><img src="assets/screenshots/02_scan_complete.png" alt="Analytics"></td>
    <td width="33%"><img src="assets/screenshots/03_settings_panel.png" alt="Configuration"></td>
  </tr>
  <tr align="center">
    <td><b>Command Center</b><br><small>Modular Dashboard</small></td>
    <td><b>Post-Scan Analytics</b><br><small>Completion Summary</small></td>
    <td><b>Deep Configuration</b><br><small>Granular Engine</small></td>
  </tr>
  <tr>
    <td width="33%"><img src="assets/screenshots/04_live_notification.png" alt="Telemetry"></td>
    <td width="33%"><img src="assets/screenshots/05_scan_results.png" alt="Data Intelligence"></td>
    <td width="33%"><img src="assets/screenshots/08_live_scanning.png" alt="Live Engine"></td>
  </tr>
  <tr align="center">
    <td><b>Real-time Telemetry</b><br><small>Background Scanning</small></td>
    <td><b>Data Intelligence</b><br><small>High-Fidelity Extraction</small></td>
    <td><b>Live Engine</b><br><small>Turbo-threaded Stream</small></td>
  </tr>
  <tr>
    <td width="33%"><img src="assets/screenshots/07_history_logs.png" alt="Archive"></td>
    <td width="33%"><img src="assets/screenshots/06_toolkit_utility.png" alt="Toolkit"></td>
    <td width="33%"></td>
  </tr>
  <tr align="center">
    <td><b>Archive Intelligence</b><br><small>Centralized Log Vault</small></td>
    <td><b>The Pro Toolkit</b><br><small>Optimization Utilities</small></td>
    <td></td>
  </tr>
</table>

---

## 📖 Operational Guide

### 1. Requirements
*   **Android OS:** 11.0 (API 30) or higher.
*   **Permissions:** `INTERNET`, `MANAGE_EXTERNAL_STORAGE` (for high-speed log writing), `WAKE_LOCK`.

### 2. Deployment
1. Download the **mScanFocus-Pro-v1.0.apk** from the header button.
2. Enable "Unknown Sources" and install.
3. Grant storage permissions to ensure log integrity.

### 3. Usage Flow
1. **Input:** Place your target `.txt` files (one host per line) in `/storage/emulated/0/Download/mScanFocus/manual_scan/`.
2. **Scan:** Select your file to initiate the high-fidelity scanning engine.
3. **Analyze:** Watch live extraction or review the **Post-Scan Analytics** card.
4. **Archive:** All results are stored in the **Centralized Log Vault** for later export or Telegram upload.

### 4. File Hierarchy
```text
📂 /Download/mScanFocus/
├── 📂 manual_scan/          ← Place input files here
│   ├── 📂 xresult_manual/   ← Scanned results saved here
│   └── 📂 scanned_txt's/    ← Processed inputs moved here
└── 📂 settings/             ← Core app configurations
```

---

## ⚙️ Advanced Configuration Guide

Tailor the engine to your specific network environment using the **Deep Configuration** panel:

*   **🔌 Target Ports:** Define a comma-separated list of ports (e.g., `80,443,8080`).
*   **🧵 Thread Concurrency:** Set the number of simultaneous connection workers. Recommended: `50` for stability, `150+` for aggressive discovery.
*   **⚡ HTTP Method:** Choose between `HEAD` (Fastest), `GET`, `POST`, `PUT`, or `DELETE` based on server requirements.
*   **⏱️ Connection Timeout:** Global timeout in seconds. Increase this for high-latency or global networks.
*   **🚫 Selective 302 Filter:** Enable to bypass non-essential redirects.
*   **📝 Exclusion Patterns:** Define keywords (e.g., `recharge`, `portal`) to filter specific 302 redirects. If the redirect `Location` contains any of these patterns, the host is skipped. **Note:** If this field is left empty, the engine will skip *all* 302 redirects by default.
*   **🤖 Telegram Bot Token:** Your unique API key from @BotFather.
*   **🆔 Chat/Topic ID:** The destination ID for automated reporting. Supports private chats, channels, and specific forum topics.
*   **🏷️ Custom Caption:** Full control over your Telegram reports using dynamic variables like `{hits}`, `{method}`, and `{scantime}`.

---

## ❓ Frequently Asked Questions

**Q: Why is the scanning speed slower than expected?**  
A: Optimization is key. Reduce thread count to `30-50`, use the `HEAD` method, and ensure your device has a stable network connection.

**Q: Can I scan while the app is minimized?**
A: Yes. The **Real-time Telemetry** engine runs as a high-priority foreground service with persistent notifications.

**Q: Why am I seeing "No Results" even on active hosts?**  
A: Check your **Connection Timeout**. High-security servers may take longer to respond. Also, ensure you are testing the correct ports.

**Q: Does the app save progress if it is closed?**  
A: **Yes.** Progress is automatically cached every 100 lines. Simply reopen the app and tap **RESUME** on the dashboard.

**Q: Why is my Telegram upload failing?**  
A: Double-check your **Bot Token** and **Chat ID**. Ensure your bot has permission to post in the target channel or topic.

**Q: Where can I find my exported log files?**  
A: All data is archived in the `/Download/mScanFocus/` directory on your internal storage.

---

## 🛡️ Professional Disclaimer
This software is intended for **authorized network analysis and educational security research only**. Usage against targets without explicit permission is strictly prohibited. The developer assumes no liability for misuse.

---

<p align="center">
  <b>Developed by <a href="https://github.com/mwmQi">mwmQi</a></b><br>
  <i>Leading the edge in mobile network security tools.</i>
</p>

<p align="center">
  <a href="https://t.me/mscanfocus"><img src="https://img.shields.io/badge/Join_Telegram-0088cc?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
</p>
