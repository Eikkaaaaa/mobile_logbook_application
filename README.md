# Welcome to mobile log book app

This is the initial version for a mobile Log book application. The application functions on both iOS and Android devices, and shares the same functionality and UI on both platforms.

In the current version user can create log book events, edit them and remove them. The application is used mainly by the main page, where there are 6 hotkeys for common events that happen often while sailing. Events are stored locally in the phones SQLite database.

Future iterations are going to contain options to add vessels, download data nad share data with other users.

Possibility for a NMEA2000 integration is also planned for a later date, to import real time data from the vessel. The integration would be done via bluetooth connection.

Screenshots from the application are located in the `/screenshots` folder.



## Start the application

1. Navigate to the `/mobile` folder in terminal

2. Install dependencies

   ```bash
   npm install
   ```

3. Start the app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [Development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)

If you want to start the application on an iOS or Android device, a proper simulator needs to be installed beforehand on your local computer. The application can also be tested on your own device using the Expo Go application for mobile devices.
