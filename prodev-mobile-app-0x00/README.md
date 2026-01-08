# Welcome to your Expo app 👋

1️⃣ Steps Followed for Scaffolding

Navigated to the project directory:
cd ~/prodev-mobile-setup/prodev-mobile-app-0x00

Initialized the Expo project using the latest Expo Router template:
npx create-expo-app@latest .


Opened the home screen app/(tabs)/index.tsx and modified the default text Welcome! to:
**First App Created**

Installed dependencies and started the development server:
npx expo start
Opened the app in Expo Go on a physical device by scanning the QR code.

2️⃣ Observations from the reset-project Command
Ran the reset script:
npm run reset-project
The script asked whether to move existing files to /app-example instead of deleting them. You chose Yes (Y).

Actions performed by the reset:
Created /app-example directory.
Moved existing project folders into /app-example:
/app → /app-example/app
/components → /app-example/components
/hooks → /app-example/hooks
/constants → /app-example/constants
/scripts → /app-example/scripts

Created a new empty /app folder with basic starter files:
app/index.tsx
app/_layout.tsx

After reset, the project is clean:
You now have a fresh /app directory to start coding.

The old files are still available in /app-example for reference.
Next steps suggested by the script:
Run npx expo start to start the dev server.
Edit app/index.tsx to change the main screen.
Delete /app-example when no longer needed.