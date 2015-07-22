Cordova Component Use Case
===========================

This is an example of how to use Cordova as a part of a regular Android application that can be used by Android Studio.

This has many similarities to both an Android project and a Cordova project, and we hopefully will be moving to this new directory
structure in a future version of Android to make it easier for people to embed Cordova, and to update the project with the new tools
developed by Google instead of the legacy Eclipse plugin that is no longer supported.

The config.xml to configure plugins can be found in app/res/xml.  Unfortunately, plugins will have to be manually installed, since plugman
does not support this new directory structure.

As usual, this code is licenced under the Apache Licence v2.0
