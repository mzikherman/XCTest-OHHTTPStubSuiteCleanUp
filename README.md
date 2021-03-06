# XCTest+OHHTTPStubSuiteCleanUp

[![Version](http://cocoapod-badges.herokuapp.com/v/XCTest+OHHTTPStubSuiteCleanUp/badge.png)](http://cocoadocs.org/docsets/XCTest+OHHTTPStubSuiteCleanUp)
[![Platform](http://cocoapod-badges.herokuapp.com/p/XCTest+OHHTTPStubSuiteCleanUp/badge.png)](http://cocoadocs.org/docsets/XCTest+OHHTTPStubSuiteCleanUp)
[![Build Status](https://travis-ci.org/1aurabrown/XCTest-OHHTTPStubSuiteCleanUp.svg)](https://travis-ci.org/1aurabrown/XCTest-OHHTTPStubSuiteCleanUp)

## Usage

OHHTTPStubs does not automatically stop stubbing http requests at the end of tests. XCTest+OHHTTPStubSuiteCleanUp will tell OHHHTTPStubs to stop stubbing requests after each XCTest test method is run to avoid stubs from one test leaking into another test. There is no need to `#import` anything, XCTest+OHHTTPStubSuiteCleanUp cleans up stubs whenever XCTest's own `tearDown` method is called (after each test method).

## Requirements
OHHTTPStubs

## Installation

XCTest+OHHTTPStubSuiteCleanUp is available through [CocoaPods](http://cocoapods.org), to install
it simply add the following line to your Podfile:

    pod "XCTest+OHHTTPStubSuiteCleanUp"

## Author

Laura Brown, laura@artsy.net

## License

XCTest+OHHTTPStubSuiteCleanUp is available under the MIT license. See the LICENSE file for more info.

