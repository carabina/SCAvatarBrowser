# SCAvatarBrowser

[![Travis CI](https://travis-ci.org/luosch/SCAvatarBrowser.svg)](https://travis-ci.org/luosch/SCAvatarBrowser)
[![Version](https://img.shields.io/cocoapods/v/SCAvatarBrowser.svg?style=flat)](http://cocoadocs.org/docsets/SCAvatarBrowser/)
[![Pod Platform](http://img.shields.io/cocoapods/p/SCAvatarBrowser.svg?style=flat)](http://cocoadocs.org/docsets/SCAvatarBrowser/)
[![License](https://img.shields.io/cocoapods/l/SCAvatarBrowser.svg?style=flat)](https://github.com/luosch/SCAvatarBrowser/blob/master/LICENSE)

## Screenshots

![](https://raw.githubusercontent.com/luosch/SCAvatarBrowser/master/Screenshots/demo.gif)

## Overview

`SCAvatarBrowser` is a powerful and lightweight tool to create the view used to enlarge photos from their avatar previews.

By using `SCAvatarBrowser`, you can make your avatar scalable, draggable and storable within just one line.

```objective-c
[SCAvatarBrowser showImage:self.avatar];
```

## Installation
Using Pod

    pod 'SCAvatarBrowser'

Or drag `SCAvatarBrowser.h` and `SCAvatarBrowser.m` files into your project, and then include "`SCAvatarBrowser.h`" where needed, or in your precompiled header.

The project uses ARC and targets iOS 7.0+.

## Usage Examples

```objective-c
#import "SCAvatarBrowser.h"
...
...
...
- (void)showAvatarDetailView {
    [SCAvatarBrowser showImageView:self.avatar];
}
```

## TODO

- ~~Create one example~~ (added 2015/09/04)
- ~~Support for drag and sacle~~ (added 2015/09/08)
- ~~Support for store image to local photo library~~ (added 2015/09/08)
- ~~Add CocoaPods spec~~ (added 2015/11/11)

## License

All source code is licensed under the [MIT License](https://raw.githubusercontent.com/luosch/SCAvatarBrowser/master/LICENSE).