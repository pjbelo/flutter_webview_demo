# flutter_webview_demo

A demo for a basic webview implementation.

## Step 1 - Configuration

Install the package:

`flutter pub add webview_flutter`

In your code import the package using:

`import 'package:webview_flutter/webview_flutter.dart';`


To use the webview_flutter plugin on Android you need to set the minSDK to 19 or 20, depending which Android Platform View you want to use.

Modify your `android/app/build.gradle` file as follows:

minSdkVersion 20
targetSdkVersion 30

## Step 2 - Basic webview







