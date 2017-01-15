Demo Mode
=====================

Control Android's Demo Mode from your app.

Puts the Demo Mode controls into an understandable API to use for debugging or in screenshot apps.
<br/>Sending Demo Mode broadcasts is as easy as `sendBroadcast(new NotificationsBuilder().visible(false).build())`.
<br/>Get a [`DemoModeInitializer`](demomode/src/main/java/com/nightlynexus/demomode/DemoModeInitializer.java) via `DemoMode.initializer(Context)` to handle granting permissions from an app.

![](images/example.jpg)

Download
--------

Gradle:

```groovy
compile 'com.nightlynexus.demomode:demomode:0.1.1'
```

License
--------

    Copyright 2016 Eric Cochran

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
