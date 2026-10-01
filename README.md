<p align="center"><img src="soggywaffle.png" alt="SoggyWaffle" width="128" height="128"></p>

<h1 align="center">SoggyWaffle</h1>

<p align="center"><b>Surprisingly crispy AI agents, running on your own computer.</b></p>

<p align="center"><a href="https://github.com/JoshDiesAtTheEnd/soggywaffle-releases/releases/latest"><b>⬇ Download the latest version</b></a></p>

## Install SoggyWaffle

SoggyWaffle runs entirely on your own computer — your bots, chats, files and email never leave it.

**You'll need:** Windows 10/11 or a 64-bit Linux desktop, about 10 GB of free disk space, and ideally an NVIDIA graphics card with 8 GB of memory (it works without one, just slower).

### 1. Install Ollama (the AI engine)

- **Windows:** download and run the installer from https://ollama.com/download/windows
- **Linux:** open a terminal and run:
  ```
  curl -fsSL https://ollama.com/install.sh | sh
  ```

### 2. Install SoggyWaffle

Download from the **Assets** list at the bottom of the [latest release](https://github.com/JoshDiesAtTheEnd/soggywaffle-releases/releases/latest).

**Windows**
1. Download `SoggyWaffle-Setup.exe` and double-click it.
2. If you see *"Windows protected your PC"*, click **More info → Run anyway** (the app isn't code-signed yet).
3. Follow the installer (leave **Create a desktop shortcut** ticked). SoggyWaffle appears on your desktop and in the Start menu.
4. To keep it in your taskbar: open SoggyWaffle, right-click its taskbar icon → **Pin to taskbar**.

**Linux**
1. Download `SoggyWaffle-x86_64.AppImage`.
2. Make it runnable: right-click it → **Properties → Permissions → Allow executing as program**, or in a terminal:
   ```
   chmod +x ~/Downloads/SoggyWaffle-x86_64.AppImage
   ```
3. Double-click it. On first launch it adds itself to your app menu, your desktop and your dock (Ubuntu/GNOME).
   - On other desktops, right-click its dock/taskbar icon → **Pin** or **Add to favorites**.
   - If it won't open on Ubuntu 22.04+, install FUSE: `sudo apt install libfuse2`

### 3. First launch

A setup screen walks you through the rest:
1. **Download the AI model** (about 5 GB, one time).
2. **Install the bot's browser** (so bots can look things up on the web).
3. Say hi to **SoggyWaffle**, your chief of staff — ask it for anything, or to make you new bots.

### Updates

The app updates itself. When a new version is out you'll see a banner — click **Update** and it restarts on the new version.

### Good to know

- Risky actions (sending email, clicking buttons on websites, running commands) always ask you first.
- If a bot hits a captcha or login, it asks you to do that step yourself in the **Screen** panel, then carries on.
- Email is optional: connect it in Settings with an app password (Gmail, iCloud, Yahoo, Fastmail…).
