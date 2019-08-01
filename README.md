# React Native Firebase Chat
Simple and Clean one-to-one messenger and chat rooms

## Configuration
Add a `config/firebase.js` file with the following content (make sure to fill in the values from your own firebase account):

## How to run the app (pick an option)
### 1. Run the app locally using the Expo XDE app (My preferred way):
  - Install the Expo XDE app from https://docs.expo.io/versions/latest/introduction/installation
  - Open the Expo XDE app
  - Choose `Open existing project`
  - Choose the root folder location

### 2. Run the app from the command line:
  - Run `npm install -g exp` to install the Expo CLI globally
  - Navigate to the root folder location
  - To view the app on a mobile device:
      - Run `exp start` and open the Expo App on your mobile device and choose the project
  - To view the app in the simulator:
    - For iOS, run `exp ios`
    - For Android, run `exp android`

###  3. Use the `yarn start`, `yarn ios`, or `yarn android` tasks as detailed below.

  #### `yarn ios`

  Like `yarn start`, but also attempts to open your app in the iOS Simulator if you're on a Mac and have it installed.

  #### `yarn android`

  Like `yarn start`, but also attempts to open your app on a connected Android device or emulator. Requires an installation of Android build tools (see [React Native docs](https://facebook.github.io/react-native/docs/getting-started.html) for detailed setup).
