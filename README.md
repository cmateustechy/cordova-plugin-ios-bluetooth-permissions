## iOS Bluetooth Permissions Plugin for Apache Cordova

**Cordova / PhoneGap Plugin Permission Settings for NSBluetoothPeripheralUsageDescription by adding a declaration to the Info.plist file**

## Install

```
cordova plugin add cordova-plugin-ios-bluetooth-permissions --save
```

## Usage

For the changes to `plugin.xml` to take effect, please refresh the `ios.json` file (inside the `/plugin` folder):
```
$ cordova platform rm ios
$ cordova platform add ios
```

#### Customizing the prompt message shown to the user

Set the following variables on installation to customize the user prompt message.

- BLUETOOTH_USAGE_DESCRIPTION for NSBluetoothPeripheralUsageDescription

Example:
```
cordova plugin add cordova-plugin-ios-bluetooth-permissions --variable BLUETOOTH_USAGE_DESCRIPTION="your usage message" --save
```

## License

[MIT License]
