# [Cordova Brightness](https://github.com/mgcrea/cordova-plugin-brightness) [![Release](https://img.shields.io/npm/v/cordova-plugin-brightness.svg?style=flat)](https://github.com/mgcrea/cordova-plugin-brightness/releases)

This plugin provides a simple way to interact with the brightness of your device.

* This plugin is built for `cordova@^3.6`.

* This plugin currently supports both iOS and Android.


## Plugin setup

Using this plugin requires [Cordova iOS](https://github.com/apache/cordova-ios).

1. `cordova plugin add cordova-plugin-brightness`


## Javascript interface

    // After device ready, create a local alias
    var VolumeControl = cordova.plugins.brightness;

    // value should be float in range from 0 to 1.
    brightness.setBrightness(value, success, error);
    // success([-1,0-1]) float 0-1 is a brightness level, -1 represents a system default
    brightness.getBrightness(success, error);
    // prevents sleep
    brightness.setKeepScreenOn(true);



## Communication

- If you **need help**, use [Stack Overflow](http://stackoverflow.com/questions/tagged/cordova). (Tag `cordova`)
- If you'd like to **ask a general question**, use [Stack Overflow](http://stackoverflow.com/questions/tagged/cordova).
- If you **found a bug**, open an issue.
- If you **have a feature request**, open an issue.
- If you **want to contribute**, submit a pull request.


## Contributing

Patches welcome! Send a pull request. Since this is not a part of Cordova Core (which requires a CLA), this should be easier.

Please submit all pull requests the against master branch. If your pull request contains JavaScript patches or features, you should include relevant unit tests. Thanks!


