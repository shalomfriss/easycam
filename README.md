# EasyCam
The easiest way to take or select a picture in iOS, because it shouldn't take an hour

## Installation

EasyCam is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
platform :ios, '10.0'
use_frameworks!

target "[YourTarget]" do
    pod 'EasyCam', :git => 'https://github.com/shalomfriss/easycam.git'
end
```

## Usage

```swift
EasyCam.autoCorrect = false //An internal autocorrect filter that is true by default
EasyCam.shared.showActionSheet(vc: self)
EasyCam.shared.imagePickedBlock = { (image) in
    //use image here
}
```
## Author

shalomfriss, shalomfriss@gmail.com

## License

EasyCam is available under the MIT license. See the LICENSE file for more info.
