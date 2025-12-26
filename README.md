
# Preferences & Auth App

A React Native application built with Expo that demonstrates state management using Context API and local persistence with AsyncStorage. This project is developed for the **Mobile Programming - Lab 11**.

## Student Information

- **Student Name:** Ozan Duru  
- **Student ID:** 210408005  

## Features

- Mock login / logout flow
- Global authentication state with Context API
- Persistent login session using AsyncStorage
- Light / Dark theme preference
- Settings screen
- Custom hook for theme management
- Multi-screen navigation with React Navigation

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd PreferencesApp
````

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the Expo development server:

   ```bash
   npm start
   ```

4. Run on your device:

   * Scan the QR code with **Expo Go** app
   * Or use an emulator

## Project Structure

```
/screens
  LoginScreen.js
  HomeScreen.js
  SettingsScreen.js
/context
  AuthContext.js
/hooks
  useTheme.js
App.js
```

## Notes

* Login state is persisted using AsyncStorage.
* Theme preference is saved and restored across app restarts.
* Clean commit history is maintained for each lab part.

## Submission

Submit the GitHub repository link as required by the lab instructions.

````

---

Bunu koyduktan sonra README değişikliği için de bir commit atmayı unutma:

```bash
git add README.md
git commit -m "docs: update README with setup and project details"
git push
````


