# android-alipay

[![Build Status](https://cloud.drone.io/api/badges/v7lin/android-alipay/status.svg)](https://cloud.drone.io/v7lin/android-alipay)
[ ![Download](https://api.bintray.com/packages/v7lin/maven/alipay-android/images/download.svg) ](https://bintray.com/v7lin/maven/alipay-android/_latestVersion)

### snapshot

````
ext {
    latestVersion = '1.0.0-SNAPSHOT'
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
    latestVersion = '1.0.0'
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
