# Xcode developer disk images
This repository hosts all developer disk images for iOS, tvOS, watchOS

## What's New?

### tvOS
* 13.0
* 12.3

### iOS
* 13.0
* 12.3

### WatchOS
* 6.0

# Why We need disk images?
When your apple device got upgraded to new OS, the current XCode version you have used doesn't have the appropriate disk image for that OS version. This prevents you to push the build to the device.
![Why We need disk images](https://raw.githubusercontent.com/haikieu/xcode-developer-disk-image-all-platforms/master/Why%20do%20you%20need%20to%20update%20disk%20image.png)

# Where to put the new disk images?
Go to your XCode app in the Application folder, open its content and locate the appropriate platform which you're going to add the new disk image.

For convenience, you can immediately jump to these paths in Finder by Cmd+G :
+ iOS: /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport
+ tvOS: /Applications/Xcode.app/Contents/Developer/Platforms/AppletvOS.platform/DeviceSupport
+ watchOS: /Applications/Xcode.app/Contents/Developer/Platforms/WatchOS.platform/DeviceSupport

![Where is Xcode disk images](https://raw.githubusercontent.com/haikieu/xcode-developer-disk-image-all-platforms/master/where%20is%20my%20developer%20disk%20images.png)
