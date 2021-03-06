# OneSignal-Java-SDK: Simple OneSignal Java REST client

* Build status [![Travis](https://img.shields.io/travis/CurrencyFair/OneSignal-Java-SDK.svg)](https://travis-ci.org/CurrencyFair/OneSignal-Java-SDK)
* Latest release [![Maven Central](https://img.shields.io/maven-central/v/com.currencyfair/onesignal.svg)](https://search.maven.org/#search%7Cga%7C1%7Ccom.currencyfair.onesignal)
* License [![License](https://img.shields.io/github/license/CurrencyFair/OneSignal-Java-SDK.svg)](https://www.apache.org/licenses/LICENSE-2.0)

[OneSignal](https://onesignal.com/) provides Push Notification delivery and automation. This SDK is its unofficial Java REST client library.

## Usage
All you need to do is call a method from `com.currencyfair.onesignal.OneSignal` class.

This SDK provides easy to use builders for `Notification`, `App`, `Session` and `Device` objects.

All 300+ status codes returned from OneSignal will be thrown as an unchecked `com.currencyfair.onesignal.OneSignalException`.

## Build
To build:
```bash
$ git clone git@github.com:CurrencyFair/OneSignal-Java-SDK.git
$ cd OneSignal-Java-SDK/
$ mvn install
```

## Binaries
Binaries and dependency information for Maven, Ivy, Gradle and others can be found at [http://search.maven.org](http://search.maven.org/#search%7Cga%7C1%7Ccom.currencyfair.onesignal).

Replace `x.y.z` with [![Maven Central](https://img.shields.io/maven-central/v/com.currencyfair/onesignal.svg)](https://search.maven.org/#search%7Cga%7C1%7Ccom.currencyfair.onesignal) or current SNAPSHOT version.

Example for Gradle:
```groovy
compile 'com.currencyfair:onesignal:x.y.z'
```

and for Maven:
```xml
<dependency>
    <groupId>com.currencyfair</groupId>
    <artifactId>onesignal</artifactId>
    <version>x.y.z</version>
</dependency>
```

and for Ivy:
```xml
<dependency org="com.currencyfair" name="onesignal" rev="x.y.z" />
```

## Bugs and Feedback
For bugs, questions and discussions please use the [Github Issues](https://github.com/CurrencyFair/OneSignal-Java-SDK/issues).

## License

This work is copyright by CurrencyFair (<https://currencyfair.com>) and licensed under the terms of [Apache License, Version 2.0](LICENSE.txt).
