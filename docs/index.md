## Introduction

HockeySDK-tvOS implements support for using HockeyApp in your tvOS applications.

The following feature is currently supported:

1. **Collect crash reports:** If your app crashes, a crash log with the same format as from the Apple Crash Reporter is written to the device's storage. If the user starts the app again, he is asked to submit the crash report to HockeyApp. This works for both beta and letive apps, i.e. those submitted to the App Store.

2. **User Metrics:** Understand user behavior to improve your app. Track usage through daily and monthly active users, monitor crash impacted users, as well as customer engagement through session count.

3. **Update notifications:** The app will check with HockeyApp if a new version for your Ad-Hoc or Enterprise build is available. If yes, it will show an alert view with informations to the moste recent version.

4. **Authenticate:** Identify and authenticate users of Ad-Hoc or Enterprise builds

## Prerequisites

1. Before you integrate HockeySDK into your own app, you should add the app to HockeyApp if you haven't already. Read [this how-to](http://support.hockeyapp.net/kb/how-tos/how-to-create-a-new-app) on how to do it.
2. We also assume that you already have a project in Xcode and that this project is opened in Xcode 7.
3. The SDK supports tvOS 9.0.

## Release Notes

- [Changelog](Changelog)

## Guides

- [Installation & Setup](Guide-Installation-Setup)
- [Mac Desktop Uploader](http://support.hockeyapp.net/kb/services-webhooks-desktop-apps/how-to-upload-to-hockeyapp-on-a-mac)

## HowTos

- [How to do app versioning](HowTo-App-Versioning)
- [How to upload symbols for crash reporting](HowTo-Upload-Symbols)
- [How to handle crashes on startup](http://support.hockeyapp.net/kb/client-integration-ios-mac-os-x/how-to-handle-crashes-during-startup-on-ios)
- [How to add application specific log data](http://support.hockeyapp.net/kb/client-integration-ios-mac-os-x/how-to-add-application-specific-log-data-on-ios-or-osx)

## Troubleshooting

- [Symbolication doesn't work](http://support.hockeyapp.net/kb/client-integration-ios-mac-os-x/how-to-solve-symbolication-problems) (Or the rules of binary UUIDs and dSYMs)
- [Crash Reporting is not working](Troubleshooting-Crash-Reporting-Not-Working)

## Xcode Documentation

This documentation provides integrated help in Xcode for all public APIs and a set of additional tutorials and HowTos.

1. Download the [HockeySDK-tvOS documentation](http://hockeyapp.net/releases/).

2. Unzip the file. A new folder `HockeySDK-tvOS-documentation` is created.

3. Copy the content into ~`/Library/Developer/Shared/Documentation/DocSet`
