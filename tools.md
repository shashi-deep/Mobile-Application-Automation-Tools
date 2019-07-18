# Mobile Application Automation Tools  

A comprehensive curated list of Mobile Application automation frameworks, tools, libraries and software to  easily bootstrap test automation.
 and when to Use the Most Popular Automation Tools Appium and Selendroid





Table of content:


- [Android Automation Tools](#Android) 
- [Environment](#Environments)


- [Resources](#resources)
- [Other Awesome Test Automation Lists](#other-awesome-test-automation-lists)

---

## Android Automation Tools
* [Appium](http://appium.io/?source=post_page---------------------------) - An open-source mobile test automation tool to test Android and iOS applications. Developers can test native, mobile web and Hybrid mobile apps on this software. To run the tests, Appium uses WebDriver interface. It supports C#, Java, Ruby, and many other programming languages that belong to WebDriver library.
Testers can test native apps that are written in Android and iOS SDKs, mobile web apps that can be accessible through mobile browser, and hybrid apps that contain web view. Being a cross-platform tool, it allows programmers to reuse the source code amongst Android and iOS.
* [Selendroid](http://selendroid.io/) - Selendroid is a good option if you’re thinking of developing only Android apps. Its main selling point is its backward compatibility; it supports Android API 10 (Android 2.3.3) through API 19 (Android 4.4).

* [Robotium](https://code.google.com/p/robotium/) - An Android test automation framework that fully supports native and hybrid applications. Robotium makes it easy to write powerful and robust automatic black-box UI tests for Android applications. With the support of Robotium, test case developers can write function, system and user acceptance test scenarios, spanning multiple Android activities.
* [UIautomator](http://developer.android.com/tools/help/uiautomator/index.html) - Provides an efficient way to test UIs. It creates automated functional test cases that can be executed against apps on real Android devices and emulators. It includes a viewer, which is a GUI tool to scan and analyze the UI components of an Android app.
* [Espresso](https://code.google.com/p/android-test-kit/wiki/Espresso) - A pretty new test automation framework that got open-sourced just last year, making it available for developers and testers to hammer out their UIs. Espresso has an API that is small, predictable, easy to learn and built on top of the Android instrumentation framework. You can quickly write concise and reliable Android UI tests with it.

## Comparing the two Automation tools Appium and Selendroid.

### [Appium](http://appium.io/?source=post_page---------------------------) 
- A lot of the distinct advantages that Appium has over Selendroid make it a stronger choice. Unlike Selendroid, Appium supports the testing of iOS apps along with Android. It also offers an easier experience over Selendroid by not having to use an SDK, and removes the need to recompile applications to test them. This also means that the app you test is the one you ship without having to modify anything just for the purpose of testing. Appium has its own UI inspector, but the Android Studio tool, uiautomatorviewer, can be used as well.
- Although Appium cannot be used to test apps for Android APIs lower than 17, it does come with a Selendroid mode to help with that. Selendroid came bundled with Appium v1.2 onwards, and under Appium’s Selendroid mode, it can help test apps on older Android versions, but with a few limitations—such as lacking the ability to locate UI elements like Selendroid, or the ability to use the same script in either modes without modification. These limitations can be overcome by using Selendroid as a standalone tool, separate from Appium

### [Selendroid](http://selendroid.io/)
- Selendroid is a good option if you’re thinking of developing only Android apps. Its main selling point is its backward compatibility; it supports Android API 10 (Android 2.3.3) through API 19 (Android 4.4).
- Also notable is that Selendroid contains an Inspector tool which can inspect UI elements of the app being tested. Although you can find UI elements in Appium as well, the advantage that Selendroid has over Appium is that Selendroid can find UI elements for older Android versions, too.
- There are a few other features Selendroid has in its arsenal. During tests, devices can be plugged or unplugged without interrupting the test being run, also called “hot plugging.” This in turn is helped by Selendroid’s ability to interact with multiple Android devices at the same time, which includes emulators and hardware devices, saving you a lot of time in the process


## Environment

* [Hive CI](http://bbc.github.io/hive-ci/) is a CI system built around devices. Connect your physical devices to a hive and run your tests on the same platforms as your users
* [STF](https://github.com/openstf/stf) - STF (or Smartphone Test Farm) is a web application for debugging smartphones, smartwatches and other gadgets remotely, from the comfort of your browser.
* [spoon](https://github.com/square/spoon) - Distributing instrumentation tests to all your Androids. 
* [Genymotion](https://www.genymotion.com/) - Genymotion is one of the best free Android emulators on the market. The software, which is both powerful and easy to use, will be of interest to the naturally curious, as well as for Android developers.



