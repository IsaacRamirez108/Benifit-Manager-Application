# Denari - Rent Payment Management Platform

> Cross-platform fintech mobile application for automated rent payment splitting

🔗 **Related:** [Backend API](https://github.com/IsaacRamirez108/Denari-Manager-Service)

## 📱 Screenshots

[Add screenshots here]

## 🚀 Tech Stack

- **Framework:** React Native with Expo
- **Language:** TypeScript
- **Navigation:** Expo Router (file-based)
- **State Management:** React Context API
- **Storage:** AsyncStorage
- **APIs:** Google Places, REST APIs, WebView bridge

## ✨ Features

- ✅ 10-step user onboarding flow
- ✅ OTP-based authentication
- ✅ Google Places address autocomplete
- ✅ Real-time form validation
- ✅ Payment schedule calendar
- ✅ WebView bank account linking
- ✅ Payment history dashboard
- ✅ Push notifications (planned)

## 🏗️ Project Structure

```
denari/
├── app/                # Expo Router app directory
│  
├── src/                 # Source code
│   ├── components/      # Reusable UI components
│   ├── screens/         # Screen components
│   ├── constants/       # App-wide constants
│   ├── contexts/        # React Context definitions
│   ├── data/            # Mock data and data utilities
│   ├── hooks/           # Custom React hooks
│   ├── services/        # API and external service integrations
│   ├── styles/          # Global styles and themes
│   ├── types/           # TypeScript type definitions
│   └── utils/           # Utility functions
├── assets/              # Static assets (images, fonts)
└── package.json         # Project dependencies and scripts
```

## 🔐 Security

- JWT token stored in AsyncStorage with encryption
- Secure API communication (HTTPS only)
- Input sanitization and validation
- Biometric authentication (planned)

## 📦 Some Custom Components

- `AddressAutocomplete` - Google Places integration with debouncing
- `FormField` - Validated input with error handling
- `AuthContext` - JWT token management
- `ScreenWrapper` - Consistent layout wrapper
- `PaymentHistoryList` - Payment tracking UI


## Getting Started

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm start
```

## Mock Data

The application includes mock data for development and testing purposes, located in `src/data/userMockData.ts`. This includes:

- User profile information
- Rental details
- Payment history
- Virtual account information

## Tech Stack

- React Native
- Expo
- TypeScript
- Expo Router

# Create Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
# Benifit-Manager-Application
