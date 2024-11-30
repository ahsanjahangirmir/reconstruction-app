# reconstruction-app
3D Landmark Reconstruction AR Mobile App in Flutter

## Prerequisites

- Flutter SDK
- Android SDK
- VS Code
- USB cable for device connection
- Android device with Developer Options enabled

## Environment Setup

### Installing Flutter

1. Visit the [Flutter website](https://flutter.dev) to install Flutter on your operating system
2. Follow the Android Setup instructions in the installation guide to install the Android SDK
3. Verify your installation by running:
   ```bash
   flutter doctor
   ```
   You should see output similar to:
   ```
   [✓] Flutter (Channel stable, 3.16.8, on Ubuntu 22.04.5 LTS)
   [✓] Android toolchain - develop for Android devices (Android SDK version 35.0.0)
   [✓] Linux toolchain - develop for Linux desktop
   [✓] Android Studio (version 2024.1)
   [✗] VS Code (version unknown)
   [✓] Connected device (1 available)
   [✓] Network resources
   ```

### Project Setup

1. Download the `app.zip` file from the Project folder in the Resources tab
2. Unzip the file in your desired working directory
3. Open the folder in VS Code

### Device Configuration

1. Connect your Android phone to your computer using a USB cable
2. Enable USB Debugging on your device:
   - Go to `Settings` app
   - Navigate to `Developer Options`
   - Enable `USB Debugging`
3. Verify device connection in VS Code - you should see your device listed in the bottom right status bar (e.g., "2201117TG(android-arm64)")

## Running the App

1. Open a terminal in VS Code and run:
   ```bash
   flutter run
   ```
2. Wait for the app to build and install on your device
3. Once installed, locate and open the Camera App on your device
4. Press the 'Open Camera' button to access your device's camera

## Troubleshooting

- If `flutter doctor` shows any issues, resolve them before proceeding
- Make sure your device is properly connected and USB debugging is enabled
- If the camera doesn't open, check if the app has the necessary permissions

## Support

If you encounter any issues or need assistance, please open an issue in the repository.
