RUNNING WEB APP:
The web app can be installed by cloning the repository: https://github.com/rutgerssoftwareengineering/Minerva-Web-App.git . Afterwards using the terminal in the same directory of the project and input this commands: npm start
I. Troubleshooting
Deleting the node modules and package-lock.json files and reinstalling them using `npm install` may fix any initial start up errors


RUNNING PHONE APP:
Installing: 
The mobile app can be installed by cloning the repository: https://github.com/rutgerssoftwareengineering/Minerva.git  . Afterwards use the terminal in the same directory of the project and input these commands: 

Git checkout mobile
Npm install
Npm start (make sure Chrome is installed on computer)
Download “Expo” on mobile device. 
From expo window on chrome, click “tunnel” option.
If on Android: Click “scan QR Code” option on Expo app and scan QR code visible on chrome.
If on iOS: Click “Share link through Text” and send link to phone. Clicking link on the phone in message app will open Minerva Mobile App in Expo.

Troubleshooting
For this demo, you need to install expo on your phone from the app store.
You need to install npm on your computer
There may be errors or warnings after installing. If node recommends running npm audit or npm audit fix:
Go to package-lock.json file
Ctrl+F search for “braces”
“Micromatch” will have a “braces” dependency that is not above 2.0.0. 
Find a “braces” version that isn’t above 2.0.0 and replace “braces” : {...}. With     
