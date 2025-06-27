# Crop on Location - Android Application & Backend

This repository contains the Android application (`finalapp.apk` and its source code in `croponlocation`) and the backend server (`Server_crop`) for a crop recommendation system. The mobile app interacts with the server to provide location-based crop recommendations.

---

## 📱 `finalapp.apk` - Ready to Use Android Application

`finalapp.apk` is a pre-built, ready-to-install Android application file. You can directly install this APK on your Android device to use the app.

### Installation Steps:

1.  **Copy the file:** Transfer the `finalapp.apk` file to your Android device (e.g., via USB, email, or cloud storage).
2.  **Allow installation from unknown sources:** On your Android device, you will need to enable installation from unknown sources. The exact steps vary slightly by Android version, but generally, you can find this setting in:
    * `Settings > Apps & notifications > Special app access > Install unknown apps` (and then grant permission to your file browser or Chrome, etc.)
    * `Settings > Security > Install unknown apps`
    * `Settings > Security > Unknown sources` (toggle on)
3.  **Install and Use:** Locate the `.apk` file on your device using a file manager and tap on it to start the installation process. Once installed, you can open and use the application directly.

---

## 🧑‍💻 `croponlocation` - Android Application Source Code

The `croponlocation` folder contains the complete source code and files required to develop and build the Android application. This project can be opened and worked on in Android Studio.

### How to Open the Project in Android Studio:

1.  **Open Android Studio.**
2.  On the top menu bar, go to **`File`** > **`Open...`**.
3.  Navigate to and **locate the `croponlocation` folder**.
4.  **Select the `croponlocation` folder** and click `Open`.

Android Studio will then import the project, sync Gradle, and make the layouts and code available for viewing and modification.

---

## 🌐 `Server_crop` - Backend Recommendation Server

`Server_crop` refers to the backend server component of this project. Its primary function is to receive POST requests from the Android application and return crop recommendations based on the data received.

### Server Details:

* **Technology:** It is a Python-Flask web server.
* **Deployment:** The server is currently deployed and running 24 hours on Heroku, handling requests from the app.

---
