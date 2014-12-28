ObjCBSON
========

High-performance BSON serialization and deserialization in Objective-C.


[![CI Status](http://img.shields.io/travis/paulmelnikow/ObjCBSON-experimental.svg?style=flat)](https://travis-ci.org/paulmelnikow/ObjCBSON-experimental)
[![Version](https://img.shields.io/cocoapods/v/ObjCBSON-experimental.svg?style=flat)](http://cocoadocs.org/docsets/ObjCBSON-experimental)
[![License](https://img.shields.io/cocoapods/l/ObjCBSON-experimental.svg?style=flat)](http://cocoadocs.org/docsets/ObjCBSON-experimental)
[![Platform](https://img.shields.io/cocoapods/p/ObjCBSON-experimental.svg?style=flat)](http://cocoadocs.org/docsets/ObjCBSON-experimental)


Installation
------------

ObjCBSON-experimental is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```rb
pod 'ObjCBSON'
```


Example
-------

```objc
NSError **error = nil;
NSDictionary *doc = [BSONSerialization dictionaryWithBSONData:data error:error];

NSError **error = nil;
NSData *data = [BSONSerialization BSONDataWithDictionary:dictionary error:error];
```


Development
-----------

To develop on the library and run the unit tests, clone the repo, run `pod install`
from the Example directory, and open the xcworkspace.


Contribute
----------

Issue Tracker: github.com/paulmelnikow/ObjCBSON/issues
Source Code: github.com/paulmelnikow/ObjCBSON


License
-------

The project is licensed under the Apache 2.0 license.

