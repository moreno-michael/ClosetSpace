# ClosetSpace
Senior Design

These instructions are for developing with a windows computer

Before you start
1. Make an account [here](https://expo.dev)
2. Download Expo Go from iOS app store, log in to same account you just made
3. Make sure you have node.js and npm on your computer

How to set up expo
1. Open your IDE of choice and open the terminal
2. In the terminal, type " npm install -g eas-cli " (If you get an error saying script execution is not allowed, follow [this tutorial](https://winbuzzer.com/2020/07/10/how-to-enable-powershell-scripts-in-windows-10-via-powershell-execution-policy-xcxwbt/))
3. Once it finishes, type " eas login " and fill in the fields
4. Clone GitHub repo to your system and open it in your IDE
5. You can start development!

To deploy build onto your iPhone
1. Open the project in your IDE
2. Open the terminal and type " eas whoami " to make sure you are signed into your expo account on your IDE
3. Make sure you are signed into the app on your phone, ensure your phone and computer are both connected to the same WiFi network
4. In the terminal type, " npx expo start " (at this point you may need to run "npm install" in your IDE terminal if you are getting an error when trying to build the app)
5. On the Expo Go app on your phone, ClosetSpace should appear under development servers

For Macs it should be the same but if you have issues follow this video tutorial [here](https://www.youtube.com/watch?v=DloY4tyzKDA)
