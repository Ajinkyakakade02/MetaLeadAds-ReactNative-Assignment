# Meta Lead Ads – React Native

This project is a small proof of concept that connects Meta Lead Ads with a React Native mobile app. It uses a Node.js and Express backend to retrieve test leads and Socket.IO to send updates to the app.

### Tech Stack
- React Native, Expo, TypeScript
- Node.js, Express.js
- Socket.IO
- Meta Graph API

### Setup

**Backend**
```bash
cd backend
npm install
```
Add your required environment variables to a local `.env` file, then start the backend using the script in `package.json`.

**Mobile App**
```bash
cd mobile
npm install
npx expo start
```

Make sure the app is configured to connect to your running backend.

### Notes
- Test leads can be retrieved using Meta's testing tools.
- The backend uses polling to check for new leads and Socket.IO to update the mobile app.
- Lead data is stored in memory and is cleared when the backend restarts.

### Demo
- [Live Demo](https://www.loom.com/share/59500a2802494345b1a25fd19b99c24b)
- [Code Walkthrough](https://www.loom.com/share/1e147e85c5ee44e18214062bc16fb7cf)

**GitHub:** [Ajinkyakakade02](https://github.com/Ajinkyakakade02)
