# flutter-starter-kit
My beginner Flutter project — exploring layouts, state management, and Flutter basics. A practice repo for learning Flutter step by step.

<p align="center">
  <img src="https://docs.flutter.dev/assets/images/branding/flutter/logo/default.svg" width="300">
</p>


# 🔽 Where to Download Flutter SDK

👉 Official site (always latest & safest):

https://docs.flutter.dev/get-started/install

That’s the official Flutter installation page from Google.

# Path Setting

Once you’ve downloaded and extracted the `Flutter` SDK, you need to set the PATH so that you can run flutter from anywhere in your terminal.

# 🔧 Setting up Flutter SDK on Windows

## 1. Download & Extract Flutter
- Go to the official [Flutter Windows Install Page](https://docs.flutter.dev/get-started/install/windows).  
- Download the latest **Stable ZIP** (e.g., `flutter_windows_x.x.x-stable.zip`).  
- Extract it to a folder (recommended path):  

C:\src\flutter


---

## 2. Add Flutter to PATH
1. Press **Win + R**, type `sysdm.cpl`, and press Enter.  
2. Go to **Advanced** → **Environment Variables**.  
3. Under **System variables**, find and select `Path`, then click **Edit**.  
4. Click **New** and add the Flutter `bin` path:

C:\src\flutter\bin

5. Click **OK** to save and close all dialogs.

---

## 3. Verify Installation
Open **Command Prompt** or **PowerShell** and run:
```bash
flutter --version
5. Click **OK** to save and close all dialogs.

---

## 3. Verify Installation
Open **Command Prompt** or **PowerShell** and run:
```bash
flutter --version

✅ You should see the installed Flutter version.

### 4. Run Flutter Doctor

Check for any remaining setup steps:

``flutter doctor``

This will tell you if Android Studio, device SDKs, or other tools are missing.



