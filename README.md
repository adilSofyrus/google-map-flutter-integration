
# Google Map Integration With Flutter

This Application use 

# `google_maps_flutter` 
A Flutter plugin that provides a Google Maps widget.
#
 1.  Android: 

Set the minSdkVersion in android/app/build.gradle:

` 
android
{
defaultConfig {
minSdkVersion 21
}
}
`

Specify your API key in the application manifest `android/app/src/main/AndroidManifest.xml:`

   2. iOS:
      
  In your swift code, specify your API key in the application delegate `ios/Runner/AppDelegate.swift:`
  
`import GoogleMaps`

`GMSServices.provideAPIKey("YOUR KEY HERE")`

# `location` 

This plugin for Flutter handles getting a location on Android and iOS. It also provides callbacks when the location is changed.

#1 Android 

`<uses-permission android:name="android.permission.FOREGROUND_SERVICE" />
    <uses-permission android:name="android.permission.ACCESS_BACKGROUND_LOCATION"/>
`

#2 iOS 


`NSLocationWhenInUseUsageDescription`

`NSLocationAlwaysUsageDescription`

`NSLocationAlwaysAndWhenInUseUsageDescription`


 # `flutter_polyline_points` 

 A flutter plugin that decodes encoded google polyline string into list of geo-coordinates suitable for showing route/polyline on maps


## API Reference

#### Get Google API 

Kindly ensure you use a valid google api key,

[If you need help generating api key for your project click this link](https://developers.google.com/maps/documentation/directions/get-api-key)

