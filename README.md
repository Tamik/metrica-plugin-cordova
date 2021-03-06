# AppMetrica Cordova Plugin

## Documentation
Common documentation available on [metrica official site][DOCUMENTATION]. 
Documentation for this plugin will be published soon. 

## Sample project
Sample project to use is available at [sample/][GitHubSAMPLE].

## Installation
```bash
cordova plugin add yandex-appmetrica-plugin-cordova
```

It is also possible to install via repo url directly *(not recomended)*:
```bash
cordova plugin add https://github.com/yandexmobile/metrica-plugin-cordova.git
```

## AppStore submit notice
Starting from version 1.6.0 Yandex AppMetrica became also a tracking instrument and
uses Apple idfa to attribute installs. Because of that during submitting your
application to the AppStore you will be prompted with three checkboxes to state
your intentions for idfa usage.
As Yandex AppMetrica uses idfa for attributing app installations you need to select **Attribute this app installation to a previously served
advertisement**.

## Changelog

### Version 0.1.0
* Implemented plugin for AppMetrica iOS (v2.8.0) and AppMetrica Android (v2.62).
* Provided sample.

## License
License agreement on use of Yandex AppMetrica is available at [EULA site][LICENSE]


[LICENSE]: https://yandex.com/legal/metrica_termsofuse/ "Yandex AppMetrica agreement"
[DOCUMENTATION]: https://tech.yandex.com/appmetrica/doc/mobile-sdk-dg/concepts/about-docpage/ "Yandex AppMetrica documentation"
[GitHubSAMPLE]: https://github.com/yandexmobile/metrica-plugin-cordova/tree/master/sample "Sample from reository"
