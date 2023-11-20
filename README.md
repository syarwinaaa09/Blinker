# Blinker
![blinker-high-resolution-logo-transparent](https://github.com/syarwinaaa09/Blinker/assets/114587158/214a7049-ff39-4fb9-8b05-77f351367369)

Welcome to Blinker, a Signal-inspired mobile application built using React Native with Navigation for seamless cross-platform experience, Expo for rapid development and Firebase for real-time data synchronisation.

### Features
* Real-time messaging: Enjoy instant communication with friends using Firebase for real-time updates.
* Navigation: Seamlessly navigate through the app with the power of React Navigation.
* Expo: Utilise the Expo framework for a faster and more efficient development experience.

### Prerequisites
Before you start, ensure you have the following installed:
* Node.js
* Expo CLI
* React Native CLI
* Firebase account

### Getting Started
1. Clone the repository:
```
git clone https://github.com/syarwinaaa09/blinker.git
cd blinker
```
2. Install dependencies
```
npm install
```
3. Set up Firebase:
   * Create a new project on the Firebase console.
   * Obtain your Firebase configuration object.
   * Create a `.env` file in the project root and add your Firebase configuration:
```
FIREBASE_API_KEY=your-api-key
FIREBASE_AUTH_DOMAIN=your-auth-domain
FIREBASE_PROJECT_ID=your-project-id
FIREBASE_STORAGE_BUCKET=your-storage-bucket
FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
FIREBASE_APP_ID=your-app-id
```
4. Start the app:
```
expo start
```
Follow the Expo CLI instructions to run the app on an emulator or a physical device.

### Project Structure
```
blinker/
├── assets/
│   ├── fonts/
│   └── images/
├── components/
│   ├── Chat.js
│   ├── Header.js
│   └── ...
├── screens/
│   ├── HomeScreen.js
│   ├── ChatScreen.js
│   └── ...
├── navigation/
│   ├── AppNavigator.js
│   └── ...
├── services/
│   ├── firebase.js
│   └── ...
├── App.js
└── ...
```

### Technologies Used
* React Native
* Expo
* Firebase

### Contributing
We welcome contributions! To contribute to Blinker, please follow our contribution guidelines.

### License
This project is licensed under the MIT License.
Happy coding! :)
