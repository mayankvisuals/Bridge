# Bridge

Bridge is a cross-platform file sharing app built with Flutter — designed for seamless LAN transfers between Android, Windows, and Linux devices.

---

### Features
-  Fast local file sharing over Wi-Fi (no internet required)  
-  Android Sharesheet integration with **Super Card (Swipe to Send)** feature  
-  Background service & system tray support on desktop  
-  Cross-platform compatibility (Android, Windows, Linux)  
-  Clean, modern Flutter UI  

---

### Tech Stack
- **Flutter (Dart)**
- **Socket / HTTP server** for LAN-based communication
- **Platform channels** for OS-specific background handling

---

### ⚙️ Installation

#### 🟢 **Android**
1. Go to the [Releases](../../releases) section.  
2. Download the APK file compatible with your device architecture (`arm64`, `armeabi-v7a`, or `x86_64`).  
3. Install it manually and allow the necessary permissions.  

#### 🟦 **Windows**
1. Go to the [Releases](../../releases) section.  
2. Download the file named **`BridgeSetup.exe`**.  
3. Run the setup — the app will install and minimize to the system tray when closed.

#### 🐧 **Linux (Debian-based distributions only)**  
*(Ubuntu, Linux Mint, Zorin OS, etc.)*  
1. Open a terminal and run these commands first:  
   ```bash
   sudo apt-get install libayatana-appindicator3-dev
   sudo ufw allow 5353/udp

2. Then, go to the [Releases](../../releases). Download the .deb package and install.

   ## 🎥 Demo Video
[Watch Demo](assets/demo.mp4)


   Thank You.
