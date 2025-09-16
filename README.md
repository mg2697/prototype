# Prototype Expo App

A modern React Native application built with Expo.

## 🚀 Features

- **Navigation**: React Navigation with stack navigation
- **UI Components**: Custom reusable components with consistent design system
- **Icons**: Expo Vector Icons integration
- **Gradients**: Linear gradients for beautiful UI elements
- **Safe Area**: Proper safe area handling for different devices
- **Organized Structure**: Clean folder structure for scalability

## 📱 Project Structure

```
src/
├── components/     # Reusable UI components
├── screens/        # Screen components
├── navigation/     # Navigation configuration
├── hooks/          # Custom React hooks
├── utils/          # Utility functions
└── constants/      # App constants (colors, layout, etc.)
```

## 🛠️ Installation

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm start
   ```

3. Run on specific platforms:
   ```bash
   npm run ios      # iOS simulator
   npm run android  # Android emulator
   npm run web      # Web browser
   ```

## 📚 Available Scripts

- `npm start` - Start the Expo development server
- `npm run ios` - Run on iOS simulator
- `npm run android` - Run on Android emulator
- `npm run web` - Run in web browser
- `npm run tunnel` - Start with tunnel for device testing
- `npm run build:ios` - Build for iOS
- `npm run build:android` - Build for Android

## 🎨 Design System

The app includes a comprehensive design system with:
- Color palette
- Typography scale
- Spacing system
- Border radius values
- Reusable components

## 📦 Dependencies

### Core
- **Expo**: ~54.0.7
- **React**: 19.1.0
- **React Native**: 0.81.4

### Navigation
- **@react-navigation/native**: Navigation framework
- **@react-navigation/native-stack**: Stack navigator

### UI & Design
- **@expo/vector-icons**: Icon library
- **expo-linear-gradient**: Gradient components
- **react-native-safe-area-context**: Safe area handling
- **expo-status-bar**: Status bar management

## 🚀 Getting Started

1. Make sure you have Node.js installed
2. Install Expo CLI globally: `npm install -g @expo/cli`
3. Clone this project and run `npm install`
4. Start developing with `npm start`

## 📱 Testing on Device

1. Install Expo Go app on your device
2. Run `npm start`
3. Scan the QR code with Expo Go (Android) or Camera app (iOS)

For more information, visit the [Expo documentation](https://docs.expo.dev/).
