# DTTextField

![Version](https://img.shields.io/badge/Pod-V0.2.1-green.svg)
![License](https://img.shields.io/github/license/mashape/apistatus.svg)
![Platform](https://img.shields.io/badge/Language-Swift_3.0-orange.svg)
![Xcode](https://img.shields.io/badge/Xcode-8.0-blue.svg)

![Demo](https://github.com/iDhaval/DTTextField/blob/master/DTTextField.gif?raw=true)

## Introduction

DTTextField is a UITextField library with floating placeholder and error label.

Floating placeholder inspired from [JVFloatLabeledTextField](https://github.com/jverdi/JVFloatLabeledTextField) :+1:.

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

* Xcode 8.0
* Swift 3.0

## Installation

DTTextField is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'DTTextField'
```

## Usage

1. Open a storyboard or Xib file.  
2. Drag and drop a `UITextField` to a ViewController.  
3. In Identity Inspector, replace the class from `UITextField` to `DTTextField` and the module to `DTTextField`.  

## Properties

| Property name | Type | Remark |
| ------------- |------------- | ----- |
| errorMessage | String | Add your error message to this property|
| errorFont | UIFont | Change font of error text |
| showError | Bool | Use to toggle error message|
| paddingYErrorLabel | CGFloat | Error text top padding |
| floatPlaceholderColor | UIColor | To change float placeholder color |
| floatPlaceholderActiveColor | UIColor | To change float placeholder color while TextField is active(First responder)|
| floatPlaceholderFont | UIFont | Change font of float placeholder |
| paddingYFloatLabel | CGFloat | float placeholder top padding |
| placeholderColor | UIColor | change placeholder color |


### Important Properties


| Property name | Type | Remark |
| ------------- |------------- | ----- |
| dtLayer | CALayer | If you want to formate DTTextField than use dtLayer property instead of layer |
| borderColor | UIColor | Change border color of DTTextField |
| canShowBorder | Bool | Toggle border of DTTextField |

## TODO
* Add inbuilt validation

## Author

Dhaval Thanki :sunglasses:

## License

```DTTextField``` is available under the MIT license. See the [LICENSE](https://github.com/iDhaval/DTTextField/blob/master/LICENSE) file for more info.