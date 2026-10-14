# Smart Transport Card: Mobile App (Frontend)

React Native (Expo) app: one card for metro, bus and train.

## Features
- Register and log in (JWT)
- Digital card with live balance and QR code
- Tap to ride: pay the fare for metro, bus or train routes
- Recharge the card
- Trip and recharge history

## Run on your phone
1. Install **Expo Go** from the Play Store or App Store.
2. Start the backend (see the backend repo).
3. Put your computer's LAN IP in `src/config.js`.
4. Then:
```bash
npm install
npx expo start
```
5. Scan the QR code with Expo Go. Phone and computer must be on the same Wi-Fi.

## Build an installable APK
```bash
npm install -g eas-cli
eas build -p android --profile preview
```
