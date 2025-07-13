````markdown
# First Mobile App - Setup Documentation

## Objective
Document the process of setting up a React Native mobile app using the Expo Router template and record what happens when the project is reset using the reset command.

---

## 📁 Steps Followed for Scaffolding

### 1. Navigate to the Project Directory
```bash
cd prodev-mobile-setup
````

### 2. Create a New Expo Project with Expo Router Template

```bash
npx create-expo-app@latest .
```

* Chose the **Expo Router** template when prompted by the CLI.

### 3. Modify the Home Screen

* Opened: `app/(tabs)/index.tsx`
* Updated text from:

  ```tsx
  <Text className="text-2xl font-bold">Welcome!</Text>
  ```

  to:

  ```tsx
  <Text className="text-2xl font-bold">** First App Created**</Text>
  ```

### 4. Start the Application

```bash
npx expo start
```

* Scanned the QR code:

  * **iOS**: using the Camera app
  * **Android**: using the Expo Go app

---

## 🔄 Observations from `npm run reset-project`

### Command Run:

```bash
npm run reset-project
```

### Observed Behavior:

* The Metro bundler cache and any previously built JavaScript bundles were cleared.
* The development server stopped and restarted cleanly.
* Any lingering or corrupted builds were removed.
* Useful for fixing odd build behaviors or component updates not reflecting properly.
* Ensured a fresh development state without deleting the source code.

---

## Summary

The setup process for the first mobile app using Expo Router was completed successfully. The app was scaffolded, modified, and tested on real devices. The `reset-project` command was confirmed to be a powerful tool for clearing state and ensuring a clean slate during development.

---

## Repository Details

* **Repository:** prodev-mobile-setup
* **Directory:** `prodev-mobile-app-0x00`
* **Key Files:**

  * `README.md`
  * `app-example/app/(tabs)/index.tsx`
  * `app-example/constants/Colors.tsx`

---

🚀 First app successfully scaffolded and tested!

```
```
