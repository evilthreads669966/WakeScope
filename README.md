[![Release](https://jitpack.io/v/evilthreads669966/wakescope.svg)](https://jitpack.io/#evilthreads669966/wakescope)&nbsp;&nbsp;[![API](https://img.shields.io/badge/API-14%2B-brightgreen.svg?style=plastic)](https://android-arsenal.com/api?level=14)
# WakeScope
### An Android library that gives you a KTX scoping function that keeps your processor awake.
## User Instructions
1. Add the JitPack repository to your project's build.gradle
```gradle
allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}
```
2. Add the dependency to your app's build.gradle
```gradle
dependencies {
        implementation 'com.github.evilthreads669966:wakescope:2.0'
}
```
3. Subclass WakeService and override Intent.doWork()
```kotlin
wakeScope {
    //do work
}
```
### Important To Know
- wakeScope has a receiver of type context
- you can pass in a timeout period to wakeScope
## Ask a Question?
- Use [Github issues](https://github.com/evilthreads669966/wakescope/issues)
- Send an email to evilthreads669966@gmail.com

## Reporting issues
Found a bug on a specific feature? Open an issue on [Github issues](https://github.com/evilthreads669966/wakescope/issues)

## Contributing

SMS Backdoor is released under the [Apache 2.0 license](https://github.com/evilthreads669966/wakescope/blob/master/LICENSE). If you would like to contribute
something, or simply want to hack then this document should help you get started.

### Code of Conduct
- Please refrain from using any profanity
- Please be respectful on [GitHub Issues](https://github.com/evilthreads669966/wakescope/issues)
- Have fun

### [Pull Requests](https://github.com/evilthreads669966/wakescope/pulls)
- Please create a branch prefixed with what you're working on.
    - FEATURE_ADDING_SOMETHING
    - BUG_FIXING_SOMETHING
    - REFACTOR_CHANGING_SOMETHING
- Once you're done with your commits to this branch hit a [pull request](https://github.com/evilthreads669966/wakescope/pulls) off and I'll look at it and most likely accept it if it looks good.

### Using [GitHub Issues](https://github.com/evilthreads669966/wakescope/issues)
We use [GitHub issues](https://github.com/evilthreads669966/wakescope/issues) to track bugs and enhancements.
- If you find a bug please fill out an issue report. Provide as much information as possible.
- If you think of a great idea please fill out an issue as a proposal for your idea.

### Code Conventions
None of these is essential for a pull request, but they will all help.  They can also be
added after the original pull request but before a merge.

- We use idiomatic kotlin conventions
- Add yourself as an `@author` to the `.kt` files that you modify or create.
- Add some comments
- A few unit tests would help a lot as well -- someone has to do it.
- If you are able to provide a unit test then do.
    - Because of the types of libraries I develop often times it is hard to test.


### Working with the code
If you don't have an IDE preference we would recommend that you use
[Android Studio](https://developer.android.com/studio/)
## Contributors
This project exists thanks to all the people who contribute.
<a href="https://github.com/evilthreads669966/wakescope/graphs/contributors"><img src="https://opencollective.com/wakescope/contributors.svg?width=890&button=false" /></a>
## Talking about WakeScope
### Articles
## License
```
Copyright 2020 Chris Basinger

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
