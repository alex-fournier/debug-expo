> **UPDATE:** it now works with Expo SDK 47

Steps to reproduce the crash on iOS simulator:

1. `npm i`
1. `eas login`
1. `eas build:configure`
1. `eas build -p ios --local --clear-cache`
1. Drag and drop app file into your simulator
1. Launch app, it crashes :'(
