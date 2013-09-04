RxJava Android Example
======================

A proof-of-concept implementation of [FRP](http://en.wikipedia.org/wiki/Functional_reactive_programming) in Android. It uses [RxJava](https://github.com/Netflix/RxJava) and some sugar to connect Android components to `Observable`s.

The idea is to improve RxJava to be used like
[ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa) is used for iOS/OS X. I intent to use this project as a laboratory for experimenting with APIs and implementation as still serve as some living example of the pattern applied to the Android world.

Take a look into
[ComposeMessageActivity](app/src/main/java/com/example/rx/ComposeMessageActivity.java) for more details.

License
-------

    Copyright 2013 Andrew Rosa

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
