# cordova-plugin-ios-frameworks

If there are any additional frameworks you want in your iOS build, but they have not been set via another plugin, you can add them in your Xcode project, but on your next Build or Prepare you will find they are missing. This plugin is made to specifically add those plugins so they will always be there when you go to build, prepare, run or archive your app.

Just edit the example frameworks in the plugin.xml file to automatically add them on build/prepare.
There are currently some frameworks added there as examples. Be sure to remove those you don't need and add those you do.

## Installation
	cordova plugin add cordova-plugin-ios-frameworks

It is also possible to install via repo url directly ( unstable )

    cordova plugin add https://github.com/NestedLooper/cordova-plugin-ios-frameworks.git


# Supported Platforms
- iOS


## Instructions
Add/Remove iOS frameworks that you would like automatically added you your Xcode project on build.
The frameworks can be edited in the plugin.xml file in this section:

        <!-- Add your additional iOS frameworks below -->
            <framework src="AdSupport.framework" />
            <framework src="libdispatch.tbd" />
        <!-- End Additional Frameworks -->





---

 		 license: Licensed to the Apache Software Foundation (ASF) under one
         or more contributor license agreements.  See the NOTICE file
         distributed with this work for additional information
         regarding copyright ownership.  The ASF licenses this file
         to you under the Apache License, Version 2.0 (the
         "License"); you may not use this file except in compliance
         with the License.  You may obtain a copy of the License at

           http://www.apache.org/licenses/LICENSE-2.0

         Unless required by applicable law or agreed to in writing,
         software distributed under the License is distributed on an
         "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
         KIND, either express or implied.  See the License for the
         specific language governing permissions and limitations
         under the License.