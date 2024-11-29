# SERVO MOTOR CONTROLLER FOR DESKTOP (macos)
This is the servo controller Electron app with UI built using a react web app. It runs from the 'macos' directory.
## Getting started
After cloning, run 

'npm install' 

in both the 'macos' and 'web' directories. 

Once dependencies are installed, cd to 'macos' directory and do 'npm start'. 

## Test with development environment
This should run 'npm start' inside the 'web' directory which will start the react server (default http://localhost:3000). Then it will start the electon app (electron .) in the 'macos' directory.

If this opens a macos window (not just a browser tab/window) and both the web url and the application window look the same, then you are good to go with building a native app.

## Build native app
If the previous step was successful, you can run 

'npm run build'

from within 'macos' directory. This should create a dist folder (and a builder folder) in which there will be an executable. For mac os on m1 mac, the executable is at

macos/dist/mac-arm64/servo-controller-macos.app

