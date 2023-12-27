# Native Device Info

This module helps in getting the device information, application information, Battery and power, Connectivity and Features, Display and Brightness, Storage Information, System Information and User and Usage Information.

## Features:

### Device Information:
#### •	GetAndriodID  
Gets the Android ID
#### •	GetAPILevel 
Gets the API level.
#### •	GetBaseOS 
The base OS build the product is based on.
#### •	GetBootloader 
The system bootloader version number.
#### •	GetBrand 
Gets the device brand.
#### •	GetBuildNumber 
Gets the application build number.
#### •	GetDevice 
The name of the industrial design.
#### •	GetDeviceID 
Gets the device ID.
#### •	GetDeviceName 
Gets the device name.
#### •	GetDeviceToken 
Gets the device token.
#### •	GetDeviceType 
Returns the device's type as a string, which will be one of:

o	Handset
o	Tablet
o	Tv
o	Desktop
o	GamingConsole
o	unknown

#### •	GetFingerprint 
A string that uniquely identifies this build.
#### •	GetHardware 
The name of the hardware (from the kernel command line or /proc).
#### •	GetManufacturer 
Gets the device manufacturer.
#### •	GetProduct 
The name of the overall product.
#### •	GetSystemName 
Gets the device OS name.
#### •	GetSystemVersion 
Gets the device OS version.
#### •	GetTotalMemory 
Gets the device total memory, in bytes.

### Application Information:

#### •	GetApplicationName 
Gets the application name.
#### •	GetBundleId 
Gets the application bundle identifier.
#### •	GetFirstInstallTime 
Gets the time at which the app was first installed, in milliseconds.

### Battery and Power:
#### •	GetBatteryLevel 
Gets the battery level of the device as a float comprised between 0 and 1.
#### •	isBatteryCharging 
Tells if the battery is currently charging.

### Display and Brightness:
#### •	GetBrightness 
Gets the current brightness level of the device's main screen. Currently iOS only. Returns a number between 0.0 and 1.0, inclusive.
#### •	GetDisplay 
A build ID string meant for displaying to the user.
#### •	isDisplayZoomed
Tells if the user changed Display Zoom to Zoomed

### Storage Information:
#### •	GetFreeDiskStorage 
Method that gets available storage size, in bytes, taking into account both root and data file systems calculation.
#### •	GetFreeDiskStorageOld 
Old implementation of method that gets available storage size, in bytes.
#### •	GetTotalDiskCapacity 
Method that gets full disk storage size, in bytes, taking into account both root and data file systems calculation.
#### •	GetTotalDiskCapacityOld 
Old implementation of method that gets full disk storage size, in bytes.

### Connectivity and Features:
#### •	GetCarrier 
Gets the carrier name (network operator).
#### •	GetCodename 
The current development codename, or the string "REL" if this is a release build.
#### •	hasDynamicIsland 
Tells if the device has a dynamic island.
#### •	hasGms 
Tells if the device supports Google Mobile Services.
#### •	hasHms 
Tells if the device supports Huawei Mobile Services.
#### •	hasNotch 
Tells if the device has a notch.
#### •	hasSystemFeature 
Tells if the device has a specific system feature.
#### •	isAirplaneMode 
Tells if the device is in Airplane Mode.
#### •	isCameraPresent 
Tells if the device has any camera now.
#### •	isEmulator
Tells if the application is running in an emulator.
#### •	isHeadphonesConnected
Tells if the device is connected to wired headset or bluetooth headphones
#### •	isLandscape
Tells if the device is currently in landscape mode.
#### •	isLocationEnabled
Tells if the device has location services turned off at the device-level (NOT related to app-specific permissions)
#### •	isLowRamDevice
Tells if the device has low RAM.
#### •	isPinOrFingerprintSet
Tells if a PIN number or a fingerprint was set for the device.
#### •	getSystemAvailableFeatures 
Returns a list of available system features on Android in a comma separated string.

### System Information:
#### •	GetHost 
Hostname
#### •	GetMaxMemory 
Returns the maximum amount of memory that the VM will attempt to use, in bytes.
#### •	GetSecurityPatch 
The user-visible security patch level.
#### •	PlatformOS 
Gets the platform OS.
#### •	supported32BitAbis 
An ordered list of 32 bit ABIs supported by this device in a comma separated string.
#### •	supported64BitAbis 
An ordered list of 64 bit ABIs supported by this device in a comma separated string.
#### •	supportedAbis 
Returns a list of supported processor architecture version in a comma separated string.

### User and Usage Information:
#### •	GetUserAgent 
Gets the device User Agent.

## Issues, suggestions and feature requests
https://github.com/bharathidas/NativeDeviceInfo/issues

## Screenshots:

![image](https://github.com/bharathidas/NativeDeviceInfo/assets/23263603/579bb22c-ef3c-403a-9360-3fe25e2e9872)

![image](https://github.com/bharathidas/NativeDeviceInfo/assets/23263603/49322760-4b99-48a6-acd1-bd971a0c7f95)

![image](https://github.com/bharathidas/NativeDeviceInfo/assets/23263603/2247bad2-c092-4bc4-9af2-22ef3793c762)

![image](https://github.com/bharathidas/NativeDeviceInfo/assets/23263603/a2a823c1-05a2-430d-8d71-8aa0b8c80992)
