<p align="center">
  <img src="http://7mnoy7.com1.z0.glb.clouddn.com/webshell/logo.png?imageView/2/w/128" />
</p>
<p align="center">
  <a href="https://github.com/djyde/WebShell/pulls">
    <img src="http://issuestats.com/github/djyde/WebShell/badge/pr?style=flat-square" />
  </a>
  <a href="https://github.com/djyde/WebShell/issues">
    <img src="http://issuestats.com/github/djyde/WebShell/badge/issue?style=flat-square" />
  </a>
  <a href="https://gitter.im/djyde/WebShell">
    <img src="https://badges.gitter.im/djyde/WebShell.svg" />
  </a>
</p>

WebShell is an OS X WebView shell, which help you easily bundle the Web Apps to native OS X app without coding.

![](http://7mnoy7.com1.z0.glb.clouddn.com/github/workflow-with-frame.png?imageView/2/w/1280)

## Requirements

- Xcode 7+ (Swift 2.0+ support)

## Quick Start

```bash

$ git clone https://github.com/djyde/WebShell.git APP_NAME

$ cd APP_NAME && open WebShell.xcodeproj

```

Edit `WebShell/ViewController.swift` and change the url whatever you like:

```swift
let SETTINGS: [String: Any]  = [

  "url": "http://jsbin.com",

  // ... other options
]
```

Finally click the `run` button to run the app.

## Bonus Features

- Standard [Notification API](https://developer.mozilla.org/en-US/docs/Web/API/notification) support

- Standard [Battery Status API](https://developer.mozilla.org/en-US/docs/Web/API/Battery_Status_API) support

## Demo

- [JS Bin](http://7mnoy7.com1.z0.glb.clouddn.com/github/JSBin.zip)

- [StackEdit](http://7mnoy7.com1.z0.glb.clouddn.com/github/StackEdit.zip) - A markdown editor

## Document

For more detail configurations, please see [document](https://github.com/djyde/WebShell/wiki/How-to-build-a-WebShell-based-application)

## Who's using WebShell

If you built any wonderful app with `WebShell`, just let me know!

# License

MIT License
