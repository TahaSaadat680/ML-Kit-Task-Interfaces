
# ML Kit Demo App

This project is an Android application that demonstrates various **ML Kit** features, including **Text Recognition**, **Face Detection**, and **Barcode Scanning**, using live camera feeds and interactive UI components. It allows users to explore and test machine learning capabilities in real-time.

## Features

- **Text Recognition**: Detect and extract text from images or live camera feeds.
- **Face Detection**: Identify faces, landmarks, and expressions (e.g., smiling probability) in real-time.
- **Barcode Scanning**: Scan and decode various barcode formats, including QR codes.

## Screenshots

| Main Screen | Text Recognition | Face Detection | Barcode Scanning |
|-------------|------------------|----------------|------------------|
| ![Main Screen](screenshots/main_screen.png) | ![Text Recognition](screenshots/text_recognition.png) | ![Face Detection](screenshots/face_detection.png) | ![Barcode Scanning](screenshots/barcode_scanning.png) |

## Prerequisites

- Android Studio (2024.2.2 or later)
- Android device or emulator with camera support
- Minimum SDK: 21
- Recommended SDK: 33

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/ml-kit-demo.git
   ```
2. Open the project in **Android Studio**.
3. Sync the Gradle files.
4. Build and run the app on a physical device or emulator.

## Permissions

The app requires the following permissions:
- **Camera**: To access the device camera for live analysis.

Ensure you grant the necessary permissions when prompted.

## How to Use

1. Launch the app.
2. Select a feature from the main screen:
   - **Text Recognition**: Point the camera at text to detect and extract it.
   - **Face Detection**: Detect faces and view details like smile probability and eye openness.
   - **Barcode Scanning**: Scan barcodes or QR codes to retrieve their content.
3. Use the interactive buttons to copy, share, or perform actions based on the detected data.

## Dark Mode Support

The app supports **Dark Mode**. Toggle the switch on the main screen to enable or disable it.

## Libraries and Tools Used

- [ML Kit](https://developers.google.com/ml-kit): Machine learning features.
- [CameraX](https://developer.android.com/training/camerax): Camera integration.
- [AndroidX](https://developer.android.com/jetpack/androidx): Modern Android development components.

## License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.

## Acknowledgments

- Google ML Kit for providing powerful machine learning tools.
- AndroidX CameraX for seamless camera integration.
