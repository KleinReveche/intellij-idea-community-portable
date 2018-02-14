<p align="center"><a href="https://github.com/portapps/intellij-idea-community-portable" target="_blank"><img width="100" src="https://github.com/portapps/intellij-idea-community-portable/blob/master/res/papp.png"></a></p>

<p align="center">
  <a href="https://github.com/portapps/intellij-idea-community-portable/releases/latest"><img src="https://img.shields.io/github/release/portapps/intellij-idea-community-portable.svg?style=flat-square" alt="GitHub release"></a>
  <a href="https://github.com/portapps/intellij-idea-community-portable/releases/latest"><img src="https://img.shields.io/github/downloads/portapps/intellij-idea-community-portable/total.svg?style=flat-square" alt="Total downloads"></a>
  <a href="https://ci.appveyor.com/project/crazy-max/intellij-idea-community-portable"><img src="https://img.shields.io/appveyor/ci/crazy-max/intellij-idea-community-portable.svg?style=flat-square" alt="AppVeyor"></a>
  <a href="https://goreportcard.com/report/github.com/portapps/intellij-idea-community-portable"><img src="https://goreportcard.com/badge/github.com/portapps/intellij-idea-community-portable?style=flat-square" alt="Go Report"></a>
  <a href="https://www.codacy.com/app/portapps/intellij-idea-community-portable"><img src="https://img.shields.io/codacy/grade/31e7c2052f2648fe866e942b8c3b0fa0.svg?style=flat-square" alt="Code Quality"></a>
  <a href="https://beerpay.io/portapps/portapps"><img src="https://img.shields.io/beerpay/portapps/portapps.svg?style=flat-square" alt="Beerpay"></a>
  <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=WQD7AQGPDEPSG"><img src="https://img.shields.io/badge/donate-paypal-7057ff.svg?style=flat-square" alt="Donate Paypal"></a>
</p>

## About

[IntelliJ IDEA Community](https://www.jetbrains.com/idea/) portable app made with 🚀 [Portapps](https://github.com/portapps).<br />
Tested on Windows 7, Windows 8.1 and Windows 10.

## Installation

There are different kinds of artifacts :

* `intellij-idea-community-portable-x.x.x-x-setup.exe` : Full portable release of IntelliJ IDEA Community as a setup.
* `intellij-idea-community-portable-win{32,64}.exe` : Only the portable binary.
* `ideaIC-x.x.win.zip` : The original release from the [official website](https://www.jetbrains.com/idea/download/#section=windows).

### Fresh installation

Install `intellij-idea-community-portable-x.x.x-x-setup.exe` where you want then run `intellij-idea-community-portable-win{32,64}.exe`.

### App already installed

If **you have already installed IntelliJ IDEA Community from the original release**, do the same thing as a fresh installation and move :

* `%USERPROFILE%\.IntelliJIdea*\config\plugins` to `data\`
* `%USERPROFILE%\.IntelliJIdea*\system\log` to `data\`
* `%USERPROFILE%\.IntelliJIdea*\config` to `data\`
* `%USERPROFILE%\.IntelliJIdea*\system` to `data\`

Run `intellij-idea-community-portable-win{32,64}.exe` and then you can [remove](https://support.microsoft.com/en-us/instantanswers/ce7ba88b-4e95-4354-b807-35732db36c4d/repair-or-remove-programs) IntelliJ IDEA Community from your computer.

### Upgrade

**For an upgrade**, simply download and install the [latest intellij-idea-community-portable setup](https://github.com/portapps/intellij-idea-community-portable/releases/latest).

## How can i help ?

All kinds of contributions are welcomed :raised_hands:!<br />
The most basic way to show your support is to star :star2: the project, or to raise issues :speech_balloon:<br />
But we're not gonna lie to each other, I'd rather you buy me a beer or two :beers:!

[![Beerpay](https://beerpay.io/portapps/portapps/badge.svg?style=beer-square)](https://beerpay.io/portapps/portapps)
or [![Paypal](https://cdn.rawgit.com/portapps/portapps/master/res/paypal.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=WQD7AQGPDEPSG)

## License

MIT. See `LICENSE` for more details.<br />
Rocket icon credit to [Squid Ink](http://thesquid.ink).
