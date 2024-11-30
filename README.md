# StockPred  Cross-Platform Development Repository

<img src="https://github.com/StockPredBangkit22024/asset/raw/b5c007b08d1624c2243d2e34257d0e8b33377da1/Cross-Platform%20Development.png" alt="Cross-Platform Development" width="800">

StockPred is a cutting-edge stock prediction tool that leverages AI to predict stock prices based on macroeconomic factors. This application is built using the Flutter framework, enabling seamless cross-platform deployment on Android, iOS, Windows, Linux, macOS, and the Web.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [How to Run](#how-to-run)
- [Built With](#built-with)
- [Contributors](#contributors)
- [License](#license)

---

## Features

- **AI-Powered Predictions**: Utilizes Deep Neural Networks to predict stock prices based on:
  - Exchange rates (USDIDR)
  - Central Bank interest rates (BI Rate)
  - Inflation rates
- **Cross-Platform**: Runs on Android, iOS, Windows, Linux, macOS, and Web.
- **Interactive UI**: A user-friendly interface built with Flutter.
- **Responsive Design**: Optimized for both desktop and mobile devices.

---

## Installation

### Prerequisites

1. Install [Flutter SDK](https://docs.flutter.dev/get-started/install).
2. Ensure you have the following:
   - Android Studio (for Android builds)
   - Xcode (for iOS builds on macOS)
   - Any IDE or text editor of your choice (e.g., VS Code).

### Clone the Repository

```bash
git clone https://github.com/StockPredBangkit22024/Cross-PlatformDevelopment.git
cd StockPred

```

### Install Dependencies

Run the following command to install the required dependencies:

```bash
flutter pub get
```

---

## Project Structure

```
StockPred/
├── android/            # Android platform-specific files
├── assets/             # Static resources (images, logos, etc.)
├── ios/                # iOS platform-specific files
├── lib/                # Main application source code
├── linux/              # Linux platform-specific files
├── macos/              # macOS platform-specific files
├── test/               # Unit tests
├── web/                # Web platform-specific files
├── windows/            # Windows platform-specific files
├── .gitignore          # Git ignored files
├── analysis_options.yaml # Code analysis settings
├── pubspec.yaml        # Project configuration
├── pubspec.lock        # Dependency lock file
└── README.md           # Project documentation
```

---

## How to Run

### For Android:
1. Connect your Android device or start an Android emulator.
2. Run the app using:
   ```bash
   flutter run
   ```

### For iOS:
1. Connect your iOS device or start the iOS simulator.
2. Run the app using:
   ```bash
   flutter run
   ```

### For Windows, Linux, macOS:
1. Ensure you have the respective build tools installed.
2. Run the app using:
   ```bash
   flutter run -d windows   # Replace 'windows' with linux or macos
   ```

### For Web:
1. Run the following command to build for web:
   ```bash
   flutter build web
   ```
2. Serve the app:
   ```bash
   flutter serve
   ```

---

## Built With

- **[Flutter](https://flutter.dev/)**: Cross-platform framework for UI development.
- **[TensorFlow](https://www.tensorflow.org/)**: For AI-based stock predictions.
- **[Dart](https://dart.dev/)**: Programming language for Flutter.

---


