# 📱 Mobile Development Environment Setup

This README documents the full setup process for configuring a mobile development environment using **React Native** with the **Expo Framework**. The setup is done on a **Windows machine** and tested on an **Android device** using **Expo Go**.

This environment is essential for upcoming mobile projects and ensures that development and testing can be done without an emulator.

---

## ✅ 1. Node.js LTS Installation (Windows)

- **Download URL:** [https://nodejs.org/](https://nodejs.org/)
- **Version Installed:** Node.js v20.x.x (LTS)
- **Installation Steps:**
  1. Downloaded the Windows Installer (.msi) for the LTS version.
  2. Launched the installer and selected default settings.
  3. Allowed system environment variables to be set automatically.
- **Verification in Terminal:**
  ```bash
  node -v  # Output: v20.x.x
  npm -v   # Output: 10.x.x
  ```

---

## ✅ 2. Visual Studio Code (VS Code)

- **Download URL:** [https://code.visualstudio.com/](https://code.visualstudio.com/)
- **Installation Steps:**
  1. Downloaded the Windows installer.
  2. Completed setup using default settings.
  3. Launched VS Code and customized the theme and settings.

- **Extensions Installed:**
  - Prettier – Code formatter
  - ESLint
  - React Native Tools
  - JavaScript and TypeScript Snippets
  - Expo Tools

---

## ✅ 3. Operating System Details

- **OS:** Windows 11 (64-bit)
- **Build:** 22H2
- Confirmed that all development tools are compatible with the Windows environment.

---

## ✅ 4. Expo Go Installation on Android Device

- **Device Type:** Android (e.g., Samsung Galaxy A52)
- **Steps:**
  1. Visited [https://expo.dev/go](https://expo.dev/go).
  2. Clicked on **"Install on Android"** which redirected to the **Google Play Store**.
  3. Installed **Expo Go** app on the Android phone.
  4. Opened the app and granted necessary permissions.

---

## ✅ 5. Expo Account Setup

- **URL:** [https://expo.dev/](https://expo.dev/)
- **Steps Followed:**
  1. Created a new account using my email address.
  2. Verified the email using the verification link.
  3. Logged into the Expo Go app using the new account.
  4. Linked Expo Go on my phone with the Expo CLI running on my computer.

---

## ✅ 6. Testing the Setup with a Sample Expo App

To verify everything was installed correctly, I created a new Expo project and ran it on my phone.

**Commands Used:**
```bash
npx create-expo-app my-first-app
cd my-first-app
npm start
```

- The Expo CLI launched a development server and opened a web interface (`localhost:19002`).
- I scanned the QR code on the web page using the **Expo Go app** on my phone.
- The app successfully opened and ran on my physical Android device.

---

## ⚠️ Challenges Faced & Resolutions

| Issue | Description | Resolution |
|------|-------------|------------|
| Expo account verification | Delay in receiving email | Checked spam/junk folder; email arrived after ~5 minutes |
| Android permissions | App wouldn’t scan QR initially | Allowed camera access for Expo Go |
| Network issues | QR code failed to connect | Ensured phone and PC were on the same Wi-Fi network |
| Confused about SDK version | Didn’t know which to choose | Chose the latest stable SDK (SDK 50) per Expo docs |

---

## ✅ Additional Notes

- The entire setup was completed without major blockers.
- My PC and Android phone are now fully configured for React Native mobile development using Expo.
- I plan to use this setup as the foundation for future mobile development projects.
- I will keep this README updated with future changes or upgrades (e.g., new SDK, new tools, etc.).

---

## 📂 Repository Structure

```
prodev-mobile-setup/
└── mobile-development-setup/
    └── README.md  ✅
```
