# Awesome Smart TV with stars

> A curated list of awesome resources for building Smart TV apps

<a href="https://github.com/vitalets/awesome-smart-tv"><img align="right" width="150" src="https://user-images.githubusercontent.com/1473072/27913047-7c3a5e60-6267-11e7-8bd1-bef2bf3cd753.png"/></a>

[Smart TV](https://en.wikipedia.org/wiki/Smart_TV) is a growing platform of TVs having access to the internet and allowing to browse web-sites and install applications. It has own ecosystem with main players like Samsung, LG, Android TV and Apple TV. In this list you will find official and third-party resources for developing Smart TV apps and communicating with TV from remote devices.

## Contents

* [Platforms](#platforms)
  * [Samsung Tizen](#samsung-tizen)
  * [LG webOS](#lg-webos)
  * [Android TV](#android-tv)
  * [Apple tvOS](#apple-tvos)
  * [Google Chromecast](#google-chromecast)
* [Cross-platform frameworks](#cross-platform-frameworks)
* [Remote control protocols](#remote-control-protocols)
* [Cross-platform tools](#cross-platform-tools)
* [Navigation libraries](#navigation-libraries)
* [Testing](#testing)
* [Misc](#misc)
* [Community](#community)

## Platforms

Below are the most popular platforms for Smart TV. The full list is [here](https://en.wikipedia.org/wiki/List_of_smart_TV_platforms_and_middleware_software).

### Samsung Tizen

#### Official resources

* [Samsung TV Developers site](http://developer.samsung.com/tv) - News, documentation and SDK downloads.
* [Tizen TV Developers site](https://developer.tizen.org/tizen/tv) - Full API documentation and guides for developing Tizen TV apps.
* [Tizen Studio](https://developer.tizen.org/development/tizen-studio/download) - IDE for TV apps development including Tizen TV Emulator.
* [Smart View SDK](http://developer.samsung.com/tv/develop/extension-libraries/smart-view-sdk/download/) - Official Android, IOS and JavaScript SDK for communication between remote device and Samsung Smart TV.
* [Samsung TV Developers Forum](http://developer.samsung.com/forum/?topCtgy=06) - Ask questions and share tips when developing apps with Samsung SDKs.
* [Samsung Smart TV Bug Bounty](https://samsungtvbounty.com) - If you find bug in Samsung TV, submit it here and get a reward $1000+.
* [vscode-extension-tizentv](https://marketplace.visualstudio.com/items?itemName=tizensdk.tizentv) - A Visual Studio Code extension that provides a lightweight IDE for Tizen application developers.
* [Wits](https://github.com/Samsung/Wits) ⭐ 123 | 🐛 15 | 🌐 JavaScript | 📅 2026-05-12 - A tool for reloading tv app's JavaScript/CSS without reinstalling the app every time you make a change.

#### Third-party remote control libraries

* [samsungctl](https://github.com/Ape/samsungctl) ⚠️ Archived - Library and command line tool for remote controlling Samsung televisions via a TCP/IP connection. It currently supports both pre-2016 TVs as well most of the modern Tizen-OS TVs with Ethernet or Wi-Fi connectivity (Python).
* [homebridge-samsung-tizen](https://github.com/tavicu/homebridge-samsung-tizen) ⭐ 678 | 🐛 89 | 🌐 JavaScript | 📅 2026-04-06 - A plugin for [Homebridge](https://github.com/nfarina/homebridge) ⭐ 25,454 | 🐛 15 | 🌐 TypeScript | 📅 2026-08-16 that allows you to control your Samsung Tizen TV with HomeKit and Siri (JavaScript).
* [samsung-tv-control](https://github.com/Toxblh/samsung-tv-control) ⭐ 198 | 🐛 21 | 🌐 TypeScript | 📅 2023-12-23 - Library for remote control Samsung TV in your Node.js
* [samsung-tv-remote](https://github.com/Badisi/samsung-tv-remote) ⭐ 57 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-05 - Node.js module to remotely control Samsung Smart TV starting from 2016 (JavaScript).
* [homebridge-samsungtv2016](https://github.com/kyleaa/homebridge-samsungtv2016) ⭐ 56 | 🐛 3 | 🌐 JavaScript | 📅 2017-01-14 - A plugin for [Homebridge](https://github.com/nfarina/homebridge) ⭐ 25,454 | 🐛 15 | 🌐 TypeScript | 📅 2026-08-16 that allows you to control your 2016 Samsung TV with HomeKit and Siri (JavaScript).
* [samsung-messagebox](https://github.com/shantanugoel/samsung-messagebox) ⭐ 56 | 🐛 0 | 🌐 Python | 📅 2014-06-05 - Python script to show notifications on Samsung TVs.
* [samsung-remote-models-2014-and-newer](https://github.com/tdudek/samsung-remote-models-2014-and-newer) ⭐ 48 | 🐛 27 | 🌐 JavaScript | 📅 2022-06-25 - Encrypted communication with the internal web service of Samsung TV models 2014+.
* [SmartCrypto](https://github.com/sectroyer/SmartCrypto) ⭐ 12 | 🐛 4 | 🌐 C | 📅 2022-08-18 - SmartView2 encrypted handshake API implementation in C/Python.

#### Other

* \[TizenTube] (<https://github.com/reisxd/TizenTube> ⭐ 1,958 | 🐛 110 | 🌐 JavaScript | 📅 2026-07-28) - A TizenBrew module that enhances your favourite streaming websites viewing experience by removing ads and adding support for Sponsorblock.
* \[TizenBrew] (<https://github.com/reisxd/TizenBrew> ⭐ 1,569 | 🐛 24 | 🌐 JavaScript | 📅 2026-05-18) - A way to experience modded websites and you can install newer apps without fighting with Tizen Studio
* [Beam-TV](https://github.com/TAGISWILD/beam-tv) ⭐ 10 | 🐛 6 | 🌐 JavaScript | 📅 2026-08-12 - Open-source, no-account media player for Samsung Tizen TVs. Plays USB and local-network (DLNA) video/audio/subtitles directly on the TV (JavaScript).
* [Tizen Studio development references](https://github.com/claromes/tizenstudio) ⚠️ Archived - Documents focused on web apps for Smart TVs e Professional Monitors, based in personal researches.
* [Identification of Samsung TV models 2008-2017](http://en.tab-tv.com/?page_id=7123) - How to get screen size, matrix type, year of development, series and other parameters from Samsung TV model name.

### LG webOS

#### Official resources

* [webOS TV Developers Site](http://webostv.developer.lge.com) - WebOS TV apps development principles, tutorials, API documentation and packaging tools.
* [webOS TV IDE + SDK](http://webostv.developer.lge.com/sdk/download/download-sdk/) - IDE for apps development including a Command Line Interface and emulator.
* [Connect SDK](http://www.svlconnectsdk.com/) - Open source framework developed by LG that connects your mobile apps with multiple media device platforms. Currently supports 8 platforms. But seems [abandoned](https://github.com/ConnectSDK/Connect-SDK-Android/issues/364) ⭐ 328 | 🐛 123 | 🌐 Java | 📅 2024-03-19.
* [webOS TV Developers Forum](http://developer.lge.com/community/forums/RetrieveForumList.dev?prodTypeCode=TV) - Ask questions, share information and learn about Smart TV app development with other developers.

#### Third-party remote control libraries

* [homebridge-webos-tv](https://github.com/merdok/homebridge-webos-tv) ⭐ 702 | 🐛 37 | 🌐 JavaScript | 📅 2026-02-17 - A plugin for [Homebridge](https://github.com/nfarina/homebridge) ⭐ 25,454 | 🐛 15 | 🌐 TypeScript | 📅 2026-08-16 which allows you to control your webOS TV.
* [LGWebOSRemote](https://github.com/klattimer/LGWebOSRemote) ⭐ 648 | 🐛 26 | 🌐 Python | 📅 2026-06-04 - Command line tool for webOS remote control of LG TVs (Python).
* [lgtv2](https://github.com/hobbyquaker/lgtv2) ⭐ 346 | 🐛 24 | 🌐 JavaScript | 📅 2022-02-04 - Node.js module for remote control of LG webOS TV via WebSocket messages (JavaScript).
* [PyWebOSTV](https://github.com/supersaiyanmode/PyWebOSTV) ⭐ 313 | 🐛 20 | 🌐 Python | 📅 2025-09-30 - A generic & entensible WebOS 3.0 Client Library (Python2, Python3).
* [lgtv2mqtt](https://github.com/hobbyquaker/lgtv2mqtt) ⭐ 109 | 🐛 8 | 🌐 JavaScript | 📅 2023-01-17 - Interface between LG WebOS Smart TVs and MQTT (JavaScript).
* [pylgtv](https://github.com/TheRealLink/pylgtv) ⚠️ Archived - Library to control webOS based LG Tv devices (Python).
* [node-red-contrib-lgtv](https://github.com/hobbyquaker/node-red-contrib-lgtv) ⭐ 59 | 🐛 48 | 🌐 JavaScript | 📅 2023-10-11 - Module for [Node-RED](https://nodered.org) allowing  remote control of LG webOS Smart TVs (JavaScript).
* [node-webos](https://github.com/WeeJeWel/node-webos) ⭐ 32 | 🐛 4 | 🌐 JavaScript | 📅 2017-12-09 - Node.js module to discover and control webOS TVs (JavaScript).
* [ares-webos-sdk](https://github.com/stevenvong/ares-webos-sdk) - webOS [CLI](http://webostv.developer.lge.com/sdk/using-webos-tv-cli/) as separate NPM module (JavaScript).
* [go-webos](github.com/kaperys/go-webos) - A small Go library for interaction with webOS TVs (golang).

#### Videos

* [LG Magic Motion Remote - Point, Click, and Control](https://youtu.be/yxu0G7jM_us) - Operate TV like a computer mouse.

#### Other

* [openlgtv.org.ru](http://openlgtv.org.ru) - A non-commercial project for legal reverse engineering and research on LG Television firmware. Seems a bit outdated but contains a lot of information.
* [Identification of LG TV models 2011-2017](http://en.tab-tv.com/?page_id=7111) - How to get screen size, matrix type, year of development, series and ohter parameters from LG TV model name.

### Android TV

#### Official resources

* [Android TV Developers site](https://developer.android.com/training/tv/start/start.html) - Documentation, tutorials and best practises for building Android TV apps.

#### Articles

* [How to develop Android TV App?](https://medium.com/@halilozel1903/how-to-develop-android-tv-app-5e251f3aa56b) - An article about developing apps for Android TV.

### Apple tvOS

#### Official resources

* [tvOS Developers Site](https://developer.apple.com/tvos/) - SDK, documentation and tutorials for developing tvOS apps.
* [TVML](https://developer.apple.com/documentation/tvml) -  Apple TV Markup Language for creating tvOS apps.

### Google Chromecast

#### Official resources

* [Google Cast SDK](https://developers.google.com/cast/) - Official Google Cast SDK documentation and tutorials.
* [TVs with Chromecast built-in](https://www.google.com/chromecast/built-in/tv/) - List of vendors supporting built-in Chromecast and advantages over traditional TV remote controller.

## Cross-platform frameworks

* [react-tv](https://github.com/raphamorim/react-tv) ⚠️ Archived - React development for TV: renderer for low memory applications and Packager for WebOS, Tizen, Orsay.
* [Smartbox](https://github.com/immosmart/smartbox) ⭐ 246 | 🐛 36 | 🌐 JavaScript | 📅 2019-01-31 - Smart TV universal library for Samsung, LG, Philips, SmartTV Aliance, STB Mag app development.
* [ZombieBox](https://github.com/interfaced/zombiebox) ⭐ 113 | 🐛 10 | 🌐 JavaScript | 📅 2025-09-07 - An open source Smart TV framework. Strongly typed JavaScript, component based, built-in D-PAD navigation management, abstract video API with DRM for all platforms. Supports many platforms like Tizen, webOS, Android TV, etc.
* [Mautilus Smart TV SDK](https://github.com/mautilus/sdk) ⭐ 102 | 🐛 13 | 🌐 JavaScript | 📅 2017-05-29 - A platform-agnostic framework for developing TV Apps. Supports Samsung, LG, Philips, Sony, Panasonic and VESTEL Smart TVs.
* [PureQML TV](https://github.com/pureqml/qmlcore-tv) ⭐ 33 | 🐛 1 | 🌐 JavaScript | 📅 2026-07-22 - A declarative front-end framework for web-based SmartTV/STB platforms. Has experimental support of Android TV.
* [TOAST](http://developer.samsung.com/tv/develop/extension-libraries/toast/) - Samsung open-source framework for multi-platform TV apps developemnt.
* [Enyo](http://enyojs.com) - LG framework for development apps for all major platforms, from phones and tablets to PCs and TVs.
* [BBC TAL](https://bbc.github.io/tal/) - An open source library for building applications for Smart TV developed by BBC engineers.

## Remote control protocols

* [DLNA](https://en.wikipedia.org/wiki/Digital_Living_Network_Alliance) - Industry-wide standard for sharing data over a home network. Depending on the DLNA-compatible devices you own, you might be able to stream films from your laptop to your TV, play an MP3 stored on your phone over your hi-fi system, or print a photo from your tablet on your home printer.
* [DIAL](http://www.dial-multiscreen.org/) - Developed by Netflix and Google, this protocol alows client devices (like smartphone, tablet, or computer) to discover apps on server devices (like a smart TV or streaming box) and launch content on them.
* [Wi-Fi Direct](https://en.wikipedia.org/wiki/Wi-Fi_Direct) - Standard enabling devices to easily connect with each other without requiring a wireless access point.
* [Miracast](https://en.wikipedia.org/wiki/Miracast) - Standard for wireless connections from devices (such as laptops, tablets, or smartphones) to displays (such as TVs, monitors or projectors). Works over Wi-Fi Direct.

## Cross-platform tools

* [Fluxcast](https://github.com/IlyaP358/fluxcast) ⭐ 330 | 🐛 14 | 🌐 Python | 📅 2026-08-07 - A user-friendly Python utility for mirroring Linux desktops to Smart TVs via Miracast and DLNA, supporting GNOME, KDE, and wlroots/Wayland.
* [smartest-tv](https://github.com/Hybirdss/smartest-tv) ⭐ 40 | 🐛 1 | 🌐 Python | 📅 2026-08-16 - CLI and MCP server for playing Netflix, YouTube, and Spotify on any smart TV by name. Deep links content across LG, Samsung, Android TV, and Roku — say "Frieren S2E8" and it plays (Python).

## Navigation libraries

* [js-spatial-navigation](https://github.com/luke-chang/js-spatial-navigation) ⭐ 429 | 🐛 39 | 🌐 JavaScript | 📅 2024-05-23 - A javascript-based implementation of Spatial Navigation.
* [react-spatial-navigation](https://github.com/NoriginMedia/react-spatial-navigation) ⚠️ Archived - HOC-based Spatial Navigation (key navigation) solution for React.
* [react-key-navigation](https://github.com/dead/react-key-navigation) ⭐ 76 | 🐛 8 | 🌐 JavaScript | 📅 2019-08-19 - Spatial Navigation components for React. Similar to the ["Focus Management"](http://bbc.github.io/tal/widgets/focus-management.html) of the [BBC TAL](https://bbc.github.io/tal/).
* [react-js-spatial-navigation](https://github.com/dead/react-js-spatial-navigation) ⭐ 34 | 🐛 11 | 🌐 JavaScript | 📅 2022-02-10 - A wrapper of js-spatial-navigation to react components.
* [lrud](https://github.com/stuart-williams/lrud) ⭐ 33 | 🐛 3 | 🌐 JavaScript | 📅 2018-09-05 - Left, Right, Up, Down. A spatial navigation library for devices with input via directional controls.

## Testing

* [Suitest](https://suite.st) - Test automation solution for Smart TVs, gaming consoles, streaming sticks etc.
* [stb-tester](https://github.com/stb-tester/stb-tester) ⭐ 194 | 🐛 30 | 🌐 Python | 📅 2026-07-25 - Automated User Interface Testing for Set-Top Boxes & Smart TVs (python).

## Misc

* [awesome-smarttv](https://github.com/linuxenko/awesome-smarttv) ⭐ 160 | 🐛 0 | 📅 2022-01-29 - Another list of Smart TV resources. Discovered after this one was already done :roll\_eyes:.
* [docker-tizen-webos-sdk](https://github.com/vitalets/docker-tizen-webos-sdk) ⭐ 132 | 🐛 3 | 🌐 Dockerfile | 📅 2025-06-18 - Docker image with Samsung Tizen CLI and LG webOS CLI. Allows to develop, build, launch and debug Smart TV apps without installing Tizen Studio and webOS SDK.
* [LIRC](http://lirc.org) - A package that allows you to decode and send infra-red signals of many (but not all) commonly used remote controls.

## Community

* [Stack Overflow](http://stackoverflow.com/questions/tagged/smart-tv)
* [Reddit](https://www.reddit.com/r/smarttv)

## Contribute

Feel free to share your experience and contribute useful extension resources by creating [new issue](https://github.com/vitalets/awesome-smart-tv/issues) ⭐ 1,402 | 🐛 3 | 📅 2026-07-26 or [pull request](https://github.com/vitalets/awesome-smart-tv/pulls) ⭐ 1,402 | 🐛 3 | 📅 2026-07-26.
Please read the [contribution guidelines](CONTRIBUTING.md) first. Thanks!

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-17._
