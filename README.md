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

------------------

## There are other iOS Tutorials with Swift 5 : 

- [Camera](https://github.com/RamdhanChoudhary/A-Simple-Camera-App-written-in-Swift)
- [TableView](https://github.com/RamdhanChoudhary/A-Simple-TableView-App-written-in-Swift)
- [CollectionView](https://github.com/RamdhanChoudhary/A-Simple-CollectionView-App-written-in-Swift)
- [Audio-Player](https://github.com/RamdhanChoudhary/A-Simpe-Audio-Player-App-in-Swift)
- [get-current-location](https://github.com/RamdhanChoudhary/A-Simple-iOS-App-to-get-current-location-and-show-it-on-Map-in--Swift)
- [CoreData](https://github.com/RamdhanChoudhary/A-Simple-iOS-App-to-use-CoreData-in-Swift)
- [PDFkit](https://github.com/RamdhanChoudhary/A-Simple-iOS-App-to-use-PDFkit-in-Swift)
- [Video-Player](https://github.com/RamdhanChoudhary/A-Simple-iOS-Video-Player-App-in-Swift)
- [Preferences](https://github.com/RamdhanChoudhary/A-Simple-iOS-App-for-Preferences-in-Swift)
- [Send-an-Email](https://github.com/RamdhanChoudhary/A-Simple-iOS-App-to-Send-an-Email-written-in-Swift)
- [Calender-Event](https://github.com/RamdhanChoudhary/A-Simple-iOS-App-for-Calender-Event-written-in-Swift)
- [Audio-Recording](https://github.com/RamdhanChoudhary/A-Simple-iOS-App-for-Audio-Recording-written-in-Swift)
- [Photos-Gallery](https://github.com/RamdhanChoudhary/A-Simple-iOS-App-to-use-Photos-Gallery-written-in-Swift)
- [TouchID](https://github.com/RamdhanChoudhary/A-Simple-iOS-App-to-use-TouchID-written-in-Swift)
- [Local-Notifications](https://github.com/RamdhanChoudhary/A-Simple-iOS-App-to-use-Local-Notifications-written-in-Swift)
- [iMessage](https://github.com/RamdhanChoudhary/A-Simple-iOS-App-to-use-iMessage-written-in-Swift)
- [TabBar-Controller](https://github.com/RamdhanChoudhary/A-Simple-iOS-App-for-TabBar-Controller-in-Swift)
- [Navigation-Bar](https://github.com/RamdhanChoudhary/A-Simple-iOS-App-for-Navigation-Bar-written-in-Swift)
- [Search-Bar](https://github.com/RamdhanChoudhary/A-Simple-iOS-App-to-use-Search-Bar-in-Swift)
- [Passing-Data-Between-Controllers](https://github.com/RamdhanChoudhary/A-Simple-iOS-App-for-Passing-Data-Between-Controllers-in-Swift)
- [Auto-Resizable-Table](https://github.com/RamdhanChoudhary/A-Simple-iOS-App-for-Auto-Resizable-Table-View-in-Swift)
- [Segues](https://github.com/RamdhanChoudhary/A-Simple-iOS-App-for-Segues-in-Storyborad)
- [Delegate](https://github.com/RamdhanChoudhary/A-Simple-iOS-App-to-use-Delegate-in-Swift)
- [Web-Request-using-URLSession](https://github.com/RamdhanChoudhary/A-Simple-iOS-App-to-make-Web-Request-using-URLSession-in-Swift)
- [Barcode-Reader](https://github.com/RamdhanChoudhary/A-Simple-iOS-App-for-Barcode-Reader-in-Swift)
- [Google-Maps](https://github.com/RamdhanChoudhary/A-Simple-iOS-App-for-Google-Maps-in-Swift)
- [Barcode Generator](https://github.com/RamdhanChoudhary/A-Simple-iOS-App-for-Barcode-Generator-in-Swift)

