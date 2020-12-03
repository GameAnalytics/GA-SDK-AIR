GA-SDK-AIR
==========

Official GameAnalytics Adobe AIR SDK.

Documentation can be found [here](https://gameanalytics.com/docs/adobe-air-sdk).

If you have any issues or feedback regarding the SDK, please contact our friendly support team [here](https://gameanalytics.com/contact).

> :information_source:
> Requirements:   
> **Adobe Air**: 24 and up   
>   
> **Build size:**   
> Note that download size differ from the actual build size.   
>   
> **Android:**   
> The SDK build size in a native Android app is only around **49Kb** and the dependecies take up to **820Kb** depending if your app already uses some of the same dependencies.   
>   
> **iOS:**   
> The SDK build size in a native iOS app is only around **242Kb** (armv7) / **259Kb** (armv8).

Supported platforms:

* iOS
* Android
* Windows
* Mac OS X

Changelog
---------
<!--(CHANGELOG_TOP)-->
**3.3.4**
* corrected ad event annotation

**3.3.3**
* fixed issue with useImei property

**3.3.2**
* improved user identifer flow for ios (ios)

**3.3.1**
* added missing enums

**3.3.0**
* added ad event

**3.2.0**
* updated user identifier flow to prepare for iOS 14 IDFA changes (ios)

**3.1.3**
* fixed ios compile error

**3.1.2**
* fixed progression events with scores (android)

**3.1.1**
* removed android dependencies (.ane files) as native android library has been refactored to not be dependent on those libraries anymore

**3.1.0**
* exposed functions to get AB testing id and variant id

**3.0.9**
* exposed onQuit function for windows and mac builds to be able to close down SDK properly

**3.0.8**
* added support for windows 64-bit

**3.0.7**
* removed facebook, gender and birthyear methods
* added auto detect app version for build field option

**3.0.6**
* A/B testing fixes

**3.0.5**
* fixed getRemoteConfigsValueAsString bug (ios)

**3.0.4**
* fixed ios build error

**3.0.3**
* remote configs fixes

**3.0.2**
* fixed events bug (ios)

**3.0.1**
* init function bug fix for android

**3.0.0**
* Remote Config calls have been updated and the old calls have deprecated. Please see GA documentation for the new SDK calls and migration guide
* A/B testing support added

**2.1.6**
* fixed extension version

**2.1.5**
* added missing android arm64 package

**2.1.4**
* updated libraries

**2.1.3**
* updated air sdk to v33 to support android 64-bit builds

**2.1.2**
* added check if log files and database can't be created

**2.1.1**
* fixes for desktop platforms

**2.1.0**
* added enable/disable event submission function

**2.0.2**
* fixed business event validation

**2.0.1**
* fixed thread hanging on shutdown for desktop platforms

**2.0.0**
* added command center functionality

**1.1.11**
* added custom dimensions to design and error events

**1.1.10**
* fixed session length bug
* fixed now allowing to add events when session is not started

**1.1.9**
* fixed progression events bug

**1.1.8**
* https fix for mac (mac)

**1.1.7**
* windows crash bug fix (windows)

**1.1.6**
* bug fix to init call on windows and mac (windows, mac)

**1.1.5**
* bug fix for end session when using manual session handling

**1.1.4**
* session length precision improvement

**1.1.3**
* custom user id bug fix

**1.1.2**
* added OS version, device model and device manufacturer to event (windows, mac)

**1.1.1**
* changed extension id from com.gameanalytics.sdk.ane to com.gameanalytics.sdk

**1.1.0**
* added Mac and Windows support

**1.0.0**
* Public release
