# 🚀 OneClick Android Emulator Setup

![macOS](https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

**OneClick Emulator Setup** is a lightning-fast, automated CLI tool designed to completely set up an Android Development environment—including the Android SDK, Command-Line Tools, Platform Tools, and an Android Virtual Device (AVD)—without the need to install the heavy 1GB+ Android Studio IDE.

Developed by **Jronix-Software Solutions**.

---

## 🎥 Demo

<img width="100%" height="225" alt="64249" src="https://github.com/user-attachments/assets/398f74c0-dcd7-4fa3-98dc-38a25e95fb6b" />


---

## ✨ Features

- **No Android Studio Required:** Skips the massive IDE download and installs only the necessary command-line tools.
- **Automated Licensing:** Automatically accepts all required Google SDK licenses.
- **Smart OS Detection:** Automatically detects macOS, Windows (Git Bash), or Linux and downloads the optimal architecture tools and system images (e.g. `arm64-v8a` for M1/M2 Macs).
- **Custom Naming & App Shortcuts (NEW):** Let's you give a custom name to your emulator, and generates a native Desktop App Shortcut!
  - **macOS:** Creates a native `.app` in your Applications folder, searchable via **Spotlight** & Launchpad!
  - **Windows:** Creates a `.bat` shortcut directly in your **Start Menu**!
  - **Linux:** Creates a `.desktop` file searchable in your App Launcher!
- **Modern Device Skins:** Automatically downloads and configures your emulator with modern device frames (Pixel 6 Pro, Pixel 6, Pixel 5) so it looks like a real phone.
- **Interactive Selection & Preview:** Allows developers to choose their preferred phone frame and even preview the frames in the browser before installing!
- **Smart Re-installation Check:** Detects if you already have emulators installed and offers to safely skip the setup process.

---

## 🚀 Quick Start (How to Run from GitHub)

You can run this tool directly from GitHub on your machine. Choose your Operating System below:

### 🍎 macOS & 🐧 Linux

Open your terminal and run the following commands:

```bash
# 1. Clone the repository
git clone https://github.com/ranasheikh64/oneclick-emulator-setup.git

# 2. Enter the directory
cd oneclick-emulator-setup

# 3. Make the script executable
chmod +x android-env

# 4. Run the setup
./android-env setup
```
*(Follow the on-screen prompts to select your modern Pixel device frame!)*

### 🪟 Windows (Git Bash)

Since this tool leverages bash scripts and command-line SDKs, Windows users should run this natively using **Git Bash** (which comes installed with Git for Windows).

1. Open **Git Bash**.
2. Run the exact same commands as macOS/Linux:
   ```bash
   git clone https://github.com/ranasheikh64/oneclick-emulator-setup.git
   cd oneclick-emulator-setup
   ./android-env setup
   ```
*(Note: Do not run this in standard CMD or PowerShell. It requires Git Bash.)*

---

## 🎮 Usage Guide

Once you have run the setup command, you can use the CLI tool to manage your emulator:

- **Start the Emulator:** (Boots up the phone with the frame you selected)
  ```bash
  ./android-env start
  ```

- **Check Environment Health:** (Verifies Java, SDK, and ADB are working)
  ```bash
  ./android-env doctor
  ```

- **List Installed Emulators:** (Shows all virtual devices you've created)
  ```bash
  ./android-env list
  ```

---

## 🛠 Prerequisites

If you run into issues, ensure you have the following installed on your system:
- `curl` and `unzip` (Usually pre-installed on Mac/Linux)
- Java (JDK 17+ is recommended)
- `git`

---

## 👨‍💻 Credits

**Developed by Jronix-Software Solutions**  
*Building powerful tools for developers.*
