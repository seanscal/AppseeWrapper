# AppseeW a wrapper for Appsee to use with Carthage

[![](https://img.shields.io/badge/carthage-compatible-brightgreen.svg)](https://github.com/Carthage/Carthage)

##Requirements

**AppseeW** is a dynamic framework, so it requires **iOS 8 or later**

##Installation

You can install the framework using **Carthage** or like a normal embedded framework.

###Carthage

Just add to your *Cartfile*

```
github "EvilClay/AppseeWrapper" ~> 2.2

```

###Embedded Framework

Clone the repository or download the Zip version and build it using the **aggregate** target which will create in your home folder a *fat framework* with slices for **arm64, armv7, armv7+ and the simulator**. You just need to add it to your project like any other framework.

##How to use it

First you need to import the Framework:

```swift

import AppseeW

```
GA's documentation states to start the service like this:

```swift

//Appsee
Appsee.start(....)

```