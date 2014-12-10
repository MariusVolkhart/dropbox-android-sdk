# Getting started with the Dropbox Android SDK

1. Include the library in your build script. See the Maven/Gradle section.
2. You'll want to start off by creating an AndroidAuthSession with your
   consumer key and secret.
3. Create a DropboxAPI object with your session.
4. Start developing the rest of your Dropbox API Android app!

## Maven/Gradle
Dropbox does not package the Android SDK for use with Maven or Gradle. This repository serves to do so.

For Gradle, add the following to your `build.gradle`
```groovy
repositories {
    maven { url "https://raw.github.com/MariusVolkhart/dropbox-android-sdk/maven" }
}

dependencies {
    compile 'io.github.mariusvolkhart.dropbox-android-sdk:library:1.6.2'
}
```
This project makes no changes to code except to facilitate packaging.
