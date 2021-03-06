# JDropDownAlert

[![Language](http://img.shields.io/badge/language-swift-brightgreen.svg?style=flat
)](https://developer.apple.com/swift)
[![Version](https://img.shields.io/cocoapods/v/trillione.svg?style=flat)](http://cocoadocs.org/docsets/JDropDownAlert)
[![License](http://img.shields.io/badge/license-MIT-lightgrey.svg?style=flat
)](http://mit-license.org)
[![Issues](https://img.shields.io/github/issues/trillione/JDropDownAlert.svg?style=flat
)](https://github.com/trillione/JDropDownAlert/issues?state=open)


#####Inspiration from RKDropDownAlert

## Demo

```Swift
// JDropDownAlert Class initialization
let alert = JDropDownAlert(typeWithDefault: .Top)

// call alertWithTitle function
alert.alertWithTitle("Hey, Beautiful!",
                         message: "Could you pass me a bottle of water?",
                         textColor: UIColor.whiteColor())
```

![alt tag](https://cloud.githubusercontent.com/assets/14218787/14765788/a2535a14-0a2c-11e6-8b4f-3a531432bc3a.gif)
--------
![alt tag](https://cloud.githubusercontent.com/assets/14218787/15170961/b18f0c38-1785-11e6-90f7-69b74f02dfa2.gif)

## Usage

```Swift
public func alertWithTitle(title: String)
                            
public func alertWithTitle(title: String,
                           textColor: UIColor)
                            
public func alertWithTitle(title: String,
                           backgroundColor: UIColor)
                           
public func alertWithTitle(title: String,
                           message: String)
                            
public func alertWithTitle(title: String,
                           message: String,
                           backgroundColor: UIColor)
                            
public func alertWithTitle(title: String,
                           message: String,
                           textColor: UIColor,
                           backgroundColor: UIColor)
```
Download and add the JDropDownAlert.swift file to your project.

## Author

- trillione, trillione1024@gmail.com
- ppth0608, ppth0608@naver.com

## License

JDropDownAlert is available under the MIT license. See the LICENSE file for more info.
