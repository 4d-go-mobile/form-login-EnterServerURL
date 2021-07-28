# Enter Server URL

[![Language][swift-shield]][swift-url]
[![check][check-shield]][check-url]
[![release][release-shield]][release-url]

First let user type the server https url of your server.

* **Type:** login

<img src="Screenshot.png" width="25%" height="25%"/>

> 💡 If the different server has not the same data, do not embedded data

## Requirements

* 4D 19.x submit 268808 minimum

## Install

Currently it is not possible to select it in projet editor but we could add it manually

* Create a `YourDatabase.4dbase/Resources/Mobile/form/login` folder.
* Then drop [release][release-url] zip content into a `EnterServerURL` folder into `YourDatabase.4dbase/Resources/Mobile/form/login`
* For this template, add `"login":"/EnterServerURL"` in the file `project.4dmobileapp` (⚠️ project must not be opened)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[swift-shield]: http://img.shields.io/badge/language-swift-orange.svg?style=flat
[swift-url]: https://developer.apple.com/swift/
[check-shield]: https://github.com/4d-go-mobile/form-login-EnterServerURL/workflows/%E2%9C%85%20check/badge.svg
[check-url]: https://github.com/4d-go-mobile/form-login-EnterServerURL/actions?query=workflow%3A%22%E2%9C%85+check%22
[release-shield]: https://img.shields.io/github/v/release/4d-go-mobile/form-login-EnterServerURL
[release-url]: https://github.com/4d-go-mobile/form-login-EnterServerURL/releases

