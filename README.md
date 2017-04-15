# Barcode to pc app

## Download
Android: https://play.google.com/store/apps/details?id=com.barcodetopc

iOS: https://itunes.apple.com/app/scienzi/id1180168368

## Setup
```
git clone https://github.com/fttx/barcode-to-pc-app/
cd barcode-to-pc-app
npm install
ionic platform add android@latest
ionic platform add ios
ionic resources
```

## Build
```
ionic run ios --device
ionic run android
```

## Release
```
ionic build ios --release
ionic build android --release -- --minSdkVersion=21

# Pre-Lollipop
ionic plugin add cordova-plugin-crosswalk-webview
ionic build android --release
```
