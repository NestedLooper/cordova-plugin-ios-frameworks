cordova-plugin-ios-frameworks
======

If there are any additional frameworks you want in your iOS build, but they have not been set via another plugin, you can add them in your Xcode project, but on your next Build or Prepare you will find they are missing. This plugin is made to specifically add those plugins so they will always be there when you go to build, prepare, run or archive your app.

Just edit the example frameworks in the plugin.xml file to automatically add them on build/prepare.
There are currently some frameworks added there as examples. Be sure to remove those you don't need and add those you do.