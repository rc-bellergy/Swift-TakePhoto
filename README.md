#  How to take, crop and save photo?

[Take and save photo](https://stackoverflow.com/questions/40854886/swift-take-a-photo-and-save-to-photo-library)

[Crop image](https://github.com/myang-git/iOS-Image-Crop-View)

[Using Objective-C Classes in Swift](https://hype.codes/how-call-objective-c-code-swift)

## Setup permission in Info.plist file

Add the strings below to Info.plist file:

### Camera
<key>NSCameraUsageDescription</key>
<string>This app will use camera.</string>

### Photo Library
<key>NSPhotoLibraryUsageDescription</key>
<string>You can select photos to attach to reports.</string>

### Save to Photo Library
<key>NSPhotoLibraryAddUsageDescription</key>
<string>Please allow access to save photo in your photo library</string>


