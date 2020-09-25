# Xcode developer disk images
This repository is to host all developer disk images for iOS, tvOS, watchOS. If your need one of them, look it up here for convenience.

## What's available?

### tvOS - [release note](https://developer.apple.com/documentation/tvos-release-notes)
* 14.2
* 14.0 
* 13.4 
* 13.3
* 13.2
* 13.0
* 12.3
* 12.2
* 12.1
* 12.0
* 11.4
* 11.3
* 11.2
* 11.1
* 11.0
* 10.2
* 10.1
* 10.0
* 9.2
* 9.1
* 9.0

### iOS - [release note](https://developer.apple.com/documentation/ios-ipados-release-notes)
* 14.2
* 14.0 
* 13.7 
* 13.6 
* 13.5 
* 13.4 
* 13.3
* 13.2
* 13.1.2
* 13.1
* 13.0
* 12.3
* 12.2
* 12.1
* 12.0
* 11.4
* 11.3
* 11.2
* 11.1
* 11.0
* 10.3
* 10.2
* 10.1
* 10.0
* 9.3
* 9.2
* 9.1
* 9.0
* 8.4
* 8.3
* 8.2
* 8.1
* 8.0

### WatchOS - [release note](https://developer.apple.com/documentation/watchos-release-notes)
* 7.1
* 7.0 
* 6.2
* 6.1
* 6.0
* 5.2
* 5.1
* 5.0
* 4.3
* 4.2
* 4.1
* 4.0
* 3.2
* 3.1
* 3.0
* 2.2
* 2.1
* 2.0

# Why We need disk images?
When your apple device got upgraded to new OS, the current XCode version you have used doesn't have the appropriate disk image for that OS version. This prevents you to push the build to the device.
![Why We need disk images](https://raw.githubusercontent.com/haikieu/xcode-developer-disk-image-all-platforms/master/Why%20do%20you%20need%20to%20update%20disk%20image.png)

# Where to put the new disk images?
Go to your XCode app in the Application folder, open its content and locate the appropriate platform which you're going to add the new disk image.

For convenience, you can immediately jump to these paths in Finder by the hotkey Cmd+Shift+G :
+ iOS: /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport
+ tvOS: /Applications/Xcode.app/Contents/Developer/Platforms/AppletvOS.platform/DeviceSupport
+ watchOS: /Applications/Xcode.app/Contents/Developer/Platforms/WatchOS.platform/DeviceSupport

![Where is Xcode disk images](https://raw.githubusercontent.com/haikieu/xcode-developer-disk-image-all-platforms/master/where%20is%20my%20developer%20disk%20images.png)
