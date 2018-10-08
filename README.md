# CheckmarkCollectionViewCell
<img align="right" src="Screenshots/CheckmarkCollectionViewCell.png">
Cell with checkbox when it `isSelected`, empty circle when not.

[![Swift Version][swift-image]][swift-url]
[![Build Status][travis-image]][travis-url]
[![License][license-image]][license-url]
[![CocoaPods Compatible](https://img.shields.io/cocoapods/v/CheckmarkCollectionViewCell.svg)](https://img.shields.io/cocoapods/v/CheckmarkCollectionViewCell.svg)  
[![Platform](https://img.shields.io/cocoapods/p/CheckmarkCollectionViewCell.svg?style=flat)](http://cocoapods.org/pods/CheckmarkCollectionViewCell)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

## Usage

```swift
class MyCell: CheckmarkCollectionViewCell {
    // get checkmark for free
}
```

### Changing Appearance

Shape:

```swift
cell.selectedImage = UIImage(named: "x")
cell.deselectedImage = UIImage(named: "o")
```

Color:

```swift
cell.tintColor = .red
```

Size:

```swift
cell.checkmarkSize = 42.0
```

Layout:

```swift
cell.checkmarkMargin = 17.0
cell.checkmarkLocation = [.top, .left]
```

## Installation

### CocoaPods:

```ruby
pod 'CheckmarkCollectionViewCell'
```


### Manually:

Copy `Sources/CheckmarkCollectionViewCell.swift` and [`MiniLayout.swift`](https://github.com/yonat/MiniLayout) to your Xcode project.

## Meta

[@yonatsharon](https://twitter.com/yonatsharon)

[https://github.com/yonat/CheckmarkCollectionViewCell](https://github.com/yonat/CheckmarkCollectionViewCell)

[swift-image]:https://img.shields.io/badge/swift-4.2-orange.svg
[swift-url]: https://swift.org/
[license-image]: https://img.shields.io/badge/License-MIT-blue.svg
[license-url]: LICENSE.txt
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[codebeat-image]: https://codebeat.co/badges/c19b47ea-2f9d-45df-8458-b2d952fe9dad
[codebeat-url]: https://codebeat.co/projects/github-com-vsouza-awesomeios-com
