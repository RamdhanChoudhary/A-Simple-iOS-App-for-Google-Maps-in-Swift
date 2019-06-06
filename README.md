# A-Simple-iOS-App-for-Google-Maps-in-Swift
A Simple Application for Google Maps in Swift 5 using iOS SDK 12.2 and Xcode IDE 10.2


**Step 1.** Add CocoaPods for Google Maps

```python
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '8.0'

target 'Simple GoogleMap' do
  pod 'GoogleMaps'
end
```

**Step 2.** Go to [Google Developers Console](https://console.developers.google.com) 

**Step 2.** Create New app, and Enable APIs for Google Maps SDK for iOS

**Step 3.** Create credentials (copy API Key)

**Step 4.** import GoogleMaps and Use the API key in App Delegate

**Step 5.** Create UIView and set class = GMSMapView and create IBOutlet

**Step 6.** Add google map init code and delegate methods in ViewController

**Step 7.** Add Location Permission in .Plist

```python
<key>NSLocationAlwaysAndWhenInUseUsageDescription</key>
<string>Application requires user’s location information while the app is running in the foreground.</string>
<key>NSLocationAlwaysUsageDescription</key>
<string>Will you allow this app to always know your location?</string>
<key>NSLocationWhenInUseUsageDescription</key>
<string>Do you allow this app to know your current location?</string>
```
