# android-alipay

[![Build Status](https://cloud.drone.io/api/badges/v7lin/android-alipay/status.svg)](https://cloud.drone.io/v7lin/android-alipay)
[![GitHub tag](https://img.shields.io/github/tag/v7lin/android-alipay.svg)](https://github.com/v7lin/android-alipay/releases)
[![API](https://img.shields.io/badge/API-16%2B-brightgreen.svg?style=flat)](https://android-arsenal.com/api?level=16)

### snapshot

````
ext {
    latestVersion = '15.5.5-SNAPSHOT'
}

allprojects {
    repositories {
        ...
        maven {
            url 'https://oss.jfrog.org/artifactory/oss-snapshot-local'
        }
        ...
    }
}
````

### release

````
ext {
    latestVersion = '15.5.5'
}

allprojects {
    repositories {
        ...
        jcenter()
        ...
    }
}
````

### usage

android
````
...
dependencies {
    ...
    implementation "io.github.v7lin:alipay-android:${latestVersion}"
    ...
}
...
````
