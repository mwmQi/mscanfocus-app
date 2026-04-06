<p align="center">
  <img src="https://img.shields.io/badge/mScanFocus-Pro_Edition-7B2CBF?style=for-the-badge&logo=android&logoColor=white" alt="mScanFocus Pro">
  <br>
  <img src="https://img.shields.io/badge/Dual_Hybrid_Engine-Enabled-00FF88?style=flat-square" alt="Hybrid Engine">
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

mScanFocus is not just a tool; it is a high-performance scanning ecosystem. By combining **Raw Socket Level connectivity** with the robustness of **Standard HTTP Clients**, we provide a scanning experience previously only possible on desktop environments.

### 🚀 Dual-Engine Hybrid Technology
*   **Lite Mode (Turbo):** Custom-engineered **TCP Socket Orchestration** that bypasses the JVM's standard network overhead for extreme throughput. Implements a specialized **Unsafe SSL/TLS Handshake Bypass**, enabling data extraction from hardened, legacy, or misconfigured servers.
*   **Standard Mode (Advanced):** A high-fidelity **Protocol Emulation Engine** built on a hardened OkHttp foundation. Utilizes **Custom Interceptor Chains** for precise header synthesis and forensic-level response analysis.

### 🎯 Intelligent Redirection Logic (302)
Automate your workflow with selective 302 handling. Automatically filter out ISP recharge portals and regional redirection while preserving valid hits.

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
    <td width="33%"><img src="assets/screenshots/09_engine_selection.png" alt="Orchestration"></td>
    <td width="33%"><img src="assets/screenshots/06_toolkit_utility.png" alt="Toolkit"></td>
    <td width="33%"><img src="assets/screenshots/07_history_logs.png" alt="Archive"></td>
  </tr>
  <tr align="center">
    <td><b>Engine Orchestration</b><br><small>Dual-Mode Toggle</small></td>
    <td><b>The Pro Toolkit</b><br><small>Optimization Utilities</small></td>
    <td><b>Archive Intelligence</b><br><small>Centralized Log Vault</small></td>
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
2. **Scan:** Select your file and choose between **Lite (Turbo)** for raw speed or **Standard (Advanced)** for deep analysis.
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

## ❓ Frequently Asked Questions

**Q: Why is Lite Mode so much faster?**
A: It operates at the TCP layer, bypassing standard HTTP overhead and heavy SSL verification handshakes.

**Q: Can I scan while the app is minimized?**
A: Yes. The **Real-time Telemetry** engine runs as a high-priority foreground service with persistent notifications.

**Q: How do I configure Telegram?**
A: Enter your Bot Token and Chat ID in the **Deep Configuration** panel. You can customize captions using dynamic placeholders like `{hits}`, `{method}`, and `{ports}`.

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
