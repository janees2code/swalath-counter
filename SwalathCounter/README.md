# Swalath / Tasbeeh Counter Android App

An Android app built with Kotlin and Jetpack Compose featuring hardware volume key counting, vibration feedback, and loop milestones.

## Features
- **Volume Key Counting**: Press Volume Up or Volume Down to increment your count without looking at the screen. The default system volume popup is suppressed.
- **Haptic Feedback**: Subtly vibrates on each count, with a distinct double vibration when completing a target cycle.
- **Customizable Loops**: Choose between 33, 100, 313, or 1000 presets.
- **Persistent Data**: Automatically retains count and target stats using SharedPreferences.

## How to Run
1. Unzip the project folder.
2. Open **Android Studio**.
3. Select **File > Open** and choose the extracted `SwalathCounter` root directory.
4. Let Gradle sync and download dependencies.
5. Connect your Android device (or start an emulator) and click **Run (Shift + F10)**.
