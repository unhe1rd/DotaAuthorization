![image](https://github.com/unhe1rd/DotaAuthorization/assets/130218904/9ea7a63e-116f-4dc5-a4df-133d9d41b8de)




# SteamLogin

Steam library for login user and retreive steam user id. Written in pure swift and support iOS 9 and more.


[![License](https://img.shields.io/cocoapods/l/SteamLogin.svg?style=flat)](http://cocoapods.org/pods/SteamLogin)
[![Platform](https://img.shields.io/cocoapods/p/SteamLogin.svg?style=flat)](http://cocoapods.org/pods/SteamLogin)

## Example


To run the example project, clone the repo, and run `pod install` from the root directory first.

Login proces is simple as:

```swift
SteamLoginVC.login(from: self) { [weak self] (user, error) in
                if let user = user {
                    self?.steamUser = user
                    self?.showSuccessAlert()
                } else {
                    self?.showErrorAlert(error)
                }
            }
```

<!--## Requirements
-->


## Installation

SteamLogin is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'SteamLogin'
```

## License

SteamLogin is available under the MIT license. See the LICENSE file for more info.


![image](https://github.com/unhe1rd/DotaAuthorization/assets/130218904/d1d8d75f-a9af-4421-a856-3d6bdf60cb15)
