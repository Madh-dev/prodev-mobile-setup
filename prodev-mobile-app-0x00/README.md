After successfully download the Expo go app
I ran npx expo start which gave error because of my network , after it was done i go for the web instead of scanning the QR code
after that i tried to and it's now working after scanning the QR code with my phone

when i ran "npm run reset-project"
i got [ npm error Missing script: "reset-project" ]
Resetting the Project

Since the latest Expo Router template no longer includes the reset-project script by default, it was added manually in the package.json file:

"reset-project": "expo prebuild --clean && rm -rf node_modules && npm install"