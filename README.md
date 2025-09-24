# flutter-nfc-manager

The Dart workspace containing packages related to NFC features for Flutter.

## Packages

|Name|Description|
|-|-|
|[ndef_record](https://github.com/okadan/flutter-nfc-manager/tree/main/packages/ndef_record)|Provides an implementation of the NFC Data Exchange Format (NDEF).|
|[nfc_manager](https://github.com/okadan/flutter-nfc-manager/tree/main/packages/nfc_manager)|Provides access to NFC features on Android and iOS.|
|[nfc_manager_ndef](https://github.com/okadan/flutter-nfc-manager/tree/main/packages/nfc_manager_ndef)|Provides NDEF abstraction using `nfc_manager` plugin.|
|[nfc_manager_felica](https://github.com/okadan/flutter-nfc-manager/tree/main/packages/nfc_manager_felica)|Provides FeliCa abstraction using `nfc_manager` plugin.|
|and more...||


This fork has been created to solve the problem described in issue [#244](https://github.com/okadan/flutter-nfc-manager/issues/244), if you need to use this fork inside your project, add the following lines inside your pubspec.yaml :

~~~
nfc_manager:
  git:
    url: git@github.com:dlopez-penbase/flutter-nfc-manager.git
    path: packages/nfc_manager
    ref: 4.0.2-dev-3
~~~