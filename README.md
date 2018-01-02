# cordova-plugin-disabledatadetectors

## Description
This plugin disables the iOS data detectors that can modify page content.
The most notable example being numbers being converted to `tel:` links.

It works by setting `webView.dataDetectorTypes` to `UIDataDetectorTypeNone`.

## Version History

### 1.1.0
* Changed plugin id.

### 1.0.2
* Added package.json for compatibility with Cordova 7.

### 1.0.1
* Minor code fix.

### 1.0.0
* Fixed code for cordova 6.
* Set minimum cordova version to 6.0.0.

### 0.1.0
* Initial release.

## License
This code is released under the MIT license.
