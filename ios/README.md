# Introduction

TrustlessSDK simplifies the integration of the Staq API into iOS applications, enhancing security and data protection. It equips developers with an extensive API designed to enable smooth communication with the Staq platform.

# Requirements

- iOS 11.0 or later
- Xcode 10.1 or newer
- CocoaPods

# Installation

To incorporate TrustlessSDK into your project, you need to edit your Podfile by adding the CocoaPods spec repository along with the following line: `pod 'TrustlessSDK'`. Your Podfile should look like this:

```ruby
source 'https://github.com/CocoaPods/Specs.git'

target 'Xcode-Project-Name' do
  pod 'TrustlessSDK'
end
```

# Initialization

In order to use the TrustlessSDK’s capabilities, you must first obtain client credentials (`clientId` and `clientSecret`) and client certificate. After securing the client certificate, embed it into your project.

Initialize the TrustlessSDK instance in AppDelegate as shown below:

```swift
func application(_ application: UIApplication,
                 didFinishLaunchingWithOptions launchOptions: [UIApplication.LaunchOptionsKey: Any]?) -> Bool
{

    TrustlessSDK.initialize(clientId: clientId, clientSecret: clientSecret)
    TrustlessSDK.configureClientCertificate(resourceName: "staq", password: "0000")

}
```

# Basic Usage

Interactions with the Staq API are conducted through the TrustlessSDK instance by utilizing specific providers (e.g., AuthProvider, CardProvider). Below is an example of user registration:

```swift
let params = CreateUserParams(email: email,
                                username: username,
                                password: password,
                                firstName: firstName,
                                lastName: lastName,
                                phoneNumber: phoneNumber)
let cancelCallback = TrustlessSDK.authProvider.registerUser(with: params) { result in
    switch result {
    case .success(let response):
        // handle response
    case .failure(let error):
        // handle error
    }
}
```

# API Reference

[API](https://staqio.github.io/trustless-sdk-docs/documentation/trustlesssdk/)

# Support

Contact support@staq.io for support.
