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

## 🛠 Prerequisites

- UNIX-based system (macOS or Linux).
- `curl` and `unzip` installed.
- Java (JDK) installed (Java 17+ is recommended for Android development).
- `git` installed.

## 🚀 Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ranasheikh64/oneclick-emulator-setup.git
   cd oneclick-emulator-setup
   ```

2. **Make the script executable:**
   ```bash
   chmod +x android-env
   ```

3. **Run the Setup Command:**
   ```bash
   ./android-env setup
   ```
   *Follow the on-screen prompts to select your modern Pixel device frame.*

4. **Start the Emulator:**
   Once setup is complete, you can easily start your emulator anytime by running:
   ```bash
   ./android-env start
   ```

## 🏥 Other Commands

- **Check Environment Health:**
  ```bash
  ./android-env doctor
  ```
- **List Installed Emulators:**
  ```bash
  ./android-env list
  ```

---

## 👨‍💻 Credits

**Developed by Jronix-Software Solutions**  
*Building powerful tools for developers.*
