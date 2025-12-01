# sandboxRADIO
Sandbox for Music Release Proofing and Analysis
# sandboxRADIO

**A High-Fidelity, Local-First WAV Player & Audio Analysis Suite.**

![Version](https://img.shields.io/badge/version-1.0.1-orange)
![License](https://img.shields.io/badge/license-MIT-blue)
![Platform](https://img.shields.io/badge/platform-Web-green)

## 🚀 No Installation Required
sandboxRADIO is a **web-based application**. It runs entirely inside your modern web browser (Chrome, Safari, Edge, Firefox). 

There are **no drivers to install**, no `.exe` or `.dmg` files to download, and no accounts to create. You simply load the page, and it works.

👉 **[Click here to Launch sandboxRADIO](https://YOUR-USERNAME.github.io/sandbox-radio/)**
*(Replace the link above with your actual GitHub Pages URL after activating it)*

---

## 🔒 Security & Privacy (Local-First)
Security is the core philosophy of sandboxRADIO. Even though this application runs in your web browser, it is **not** a cloud streaming service.

*   **Your Files Stay With You:** When you "load" a file into sandboxRADIO, it is **never** uploaded to a server. The application streams the audio directly from your computer's hard drive or your phone's storage into the browser's temporary memory.
*   **Zero Data Collection:** We do not track your listening habits, file names, or metadata.
*   **Offline Capable:** Once the page is loaded, you can disconnect from the internet entirely, and the player will continue to function perfectly.

---

## 🎛 Key Features

### 1. Professional Metering
Designed for mastering engineers and producers, the meter bridge provides broadcast-grade telemetry:
*   **LUFS Metering:** Momentary (M) and Integrated (I) loudness readings.
*   **Dynamic Range:** Real-time Peak-to-Loudness Ratio (PLR) calculation.
*   **Phase Correlation:** Detect mono compatibility issues instantly with the CORR meter.
*   **True Peak Detection:** Dedicated clip indicators and a "Max Peak" hold function with manual reset.

### 2. The Analysis Lab
A dedicated visual suite for deep audio inspection:
*   **Spectrum Analyzer:** View frequency response in standard L/R or Mid/Side modes.
*   **Oscilloscope:** Inspect waveforms with adjustable timebase zoom (10ms - 5000ms).
*   **Vector Scope (Goniometer):** Visualize stereo width and phase issues.
*   **Waterfall Plot:** View frequency intensity over time.

### 3. Smart Library Management
*   **Persistent Database:** Using IndexedDB technology, sandboxRADIO remembers your loaded library and settings even after you close the browser window.
*   **Gapless Queue:** Drag-and-drop ordering for testing album sequences.
*   **"Test End" Function:** Instantly jump to the last 10 seconds of a track to test crossfades and transitions between songs without waiting.
*   **Backup & Restore:** Export your library configuration to a JSON file to move between devices.

---

## 📱 Platform Compatibility

sandboxRADIO is responsive and adapts to your device:

*   **Desktop (Windows/Mac/Linux):** Supports folder loading, drag-and-drop, and multi-file selection.
*   **iOS (iPhone/iPad):** Fully compatible with Safari. Includes a specialized "Choose Files" flow to adhere to Apple's file security sandbox.
*   **Android:** Supports folder permissions and file selection via Chrome/Firefox.

---

## 🛠 Usage

### Hosting it yourself (Optional)
Because sandboxRADIO is a static application, you can run it offline on your own machine without a web server:

1.  Download the `index.html` and `sandboxradio_help.html` files from this repository.
2.  Place them in a folder.
3.  Double-click `index.html`.

### Loading Files
*   **Folders:** Use the "Load Folder" button to import entire albums at once (Desktop/Android).
*   **Files:** Use "Load Files" for single tracks or on iOS.
*   **Cloud Files:** If your audio is on Dropbox/WeTransfer, download/unzip them to your device first, then load them into sandboxRADIO.

---

## 🔧 Technologies Used
*   **HTML5 / CSS3**
*   **Vanilla JavaScript (ES6+)**
*   **Web Audio API** (for DSP and Analysis)
*   **IndexedDB** (for local data persistence)
*   **HTML5 Canvas** (for real-time visualization)

---

## 📄 License
This project is open source and available under the [MIT License](LICENSE).
