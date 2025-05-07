# Prometheus: Add README for ExpoFaceDetectorDemo

## Project Overview

A mobile application that demonstrates real-time face detection capabilities using Expo and React Native technologies. The app leverages the device's front-facing camera to provide instant facial analysis and detection.

### Key Features
- Real-time face detection using Expo's face detection API
- Analyzes facial characteristics in real-time, including:
  - Eye closure detection
  - Winking recognition
  - Smile detection
- Front-facing camera integration
- Simple and intuitive user interface

### Benefits
- Demonstrates advanced mobile computer vision techniques
- Provides a lightweight example of facial recognition technology
- Works across multiple mobile platforms (iOS and Android) using React Native
- Low-overhead implementation with fast detection mode

## Getting Started, Installation, and Setup

### Prerequisites

- Node.js (LTS version recommended)
- Yarn or npm package manager
- Expo CLI

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/facedetectordemo.git
   cd facedetectordemo
   ```

2. Install dependencies:
   ```bash
   yarn install
   # or
   npm install
   ```

### Running the App

#### Development Mode

To start the development server:

```bash
yarn start
# or
npm start
```

This will launch the Expo development server. You can:
- Scan the QR code with the Expo Go app on your mobile device
- Press `a` to run on Android emulator
- Press `i` to run on iOS simulator
- Press `w` to run in web browser

#### Platform-Specific Commands

- Run on Android:
  ```bash
  yarn android
  # or
  npm run android
  ```

- Run on iOS:
  ```bash
  yarn ios
  # or
  npm run ios
  ```

- Run on Web:
  ```bash
  yarn web
  # or
  npm run web
  ```

### Additional Notes

- Ensure you have the latest version of Expo CLI installed globally:
  ```bash
  npm install -g expo-cli
  ```

- This project requires an active internet connection during development
- Mobile testing is recommended through the Expo Go app