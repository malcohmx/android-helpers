# Android Helpers
[![](https://jitpack.io/v/danimahardhika/android-helpers.svg)](https://jitpack.io/#danimahardhika/android-helpers) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) 

Android helpers collection that used for my projects.

# Gradle Dependency
Add JitPack repository to root ```build.gradle```
```Gradle
allprojects {
    repositories {
        maven { url "https://jitpack.io" }
    }
}
```
Add the dependency
```Gradle
dependencies {
    compile 'com.github.danimahardhika.android-helpers:core:$versionNumber'
    compile 'com.github.danimahardhika.android-helpers:license:$versionNumber'
    compile 'com.github.danimahardhika.android-helpers:permission:$versionNumber'
}
```

# License
```
Copyright (c) 2017 Dani Mahardhika

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```