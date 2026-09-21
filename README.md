# 🚀 OneClick Emulator Setup

**OneClick Emulator Setup** is a lightning-fast, automated CLI tool designed to completely set up an Android Development environment—including the Android SDK, Command-Line Tools, Platform Tools, and an Android Virtual Device (AVD)—without the need to install the heavy 1GB+ Android Studio IDE.

Developed by **Jronix-Software Solutions**.

---

## ✨ Features

- **No Android Studio Required:** Skips the massive IDE download and installs only the necessary command-line tools.
- **Automated Licensing:** Automatically accepts all required Google SDK licenses.
- **Smart OS Detection:** Automatically detects macOS (Intel & Apple Silicon M1/M2/M3) or Linux and downloads the optimal architecture system image (`arm64-v8a` vs `x86_64`).
- **Modern Device Skins:** Automatically downloads and configures your emulator with modern device frames (Pixel 8 Pro, Pixel 6, Pixel 5) so it looks like a real phone.
- **Interactive Selection & Preview:** Allows developers to choose their preferred phone frame and even preview the frames in the browser before installing!

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

### 🪟 Windows

Since this is a Bash script, Windows users should run this using **WSL (Windows Subsystem for Linux)** or **Git Bash**.

1. Open your **WSL Ubuntu** terminal (or Git Bash).
2. Run the exact same commands as macOS/Linux:
   ```bash
   git clone https://github.com/ranasheikh64/oneclick-emulator-setup.git
   cd oneclick-emulator-setup
   chmod +x android-env
   ./android-env setup
   ```

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
