# Demo ReactNative testing with [Detox](https://github.com/wix/Detox)

## Software Requirements
* React 17.0.2
* [React Native](https://github.com/facebook/react-native) 0.65.1
* [NVM](https://github.com/nvm-sh/nvm)
* [AppleSimulatorUtils](https://github.com/wix/AppleSimulatorUtils)
* XCode 12.5

## Create [React Native Project](https://reactnative.dev/docs/environment-setup)
```
$npx react-native init demo01
$npx react-native start
$npx react-native run-ios
```

## Run dev mode with iOS and custom configurations
```
$npm run ios
```

## Testing with [Detox](https://github.com/wix/Detox/blob/master/docs/Introduction.GettingStarted.md)
```
$npm install -g detox-cli
$npm install detox --save-dev
```

Initial detox in project
```
$detox init
```

Building with Detox
```
$npm run build-e2e
```

Run tests with Detox
```
$npm run test-e2e
```




