CredentialsManager
===================

```CredentialsManager``` is used by most of the tools part of the [fastlane.tools](https://fastlane.tools) toolchain.

Every code, related to your username and password can be found here: [password_manager.rb](https://github.com/KrauseFx/CredentialsManager/blob/master/lib/credentials_manager/password_manager.rb)

## Storing in the Keychain
By default, when entering your Apple credentials, they will be stored in the Keychain from Mac OS X. You can easily delete them, by opening the "Keychain App" switching to *All Items* and searching for "*deliver*".

## Passing using environment variables
```
DELIVER_USER
DELIVER_PASSWORD
```

## Implement your custom solution
All ```fastlane``` tools are based on Ruby, you can take a look at the source to easily implement your own authentication solution.

Your password will only be stored locally on your computer. 

# License
This project is licensed under the terms of the MIT license. See the LICENSE file.

# Contributing

1. Create an issue to discuss about your idea
2. Fork it (https://github.com/KrauseFx/CredentialsManager/fork)
3. Create your feature branch (`git checkout -b my-new-feature`)
4. Commit your changes (`git commit -am 'Add some feature'`)
5. Push to the branch (`git push origin my-new-feature`)
6. Create a new Pull Request

