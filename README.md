This is a Kotlin Multiplatform project targeting Android, iOS.

* `/composeApp` is for code that will be shared across your Compose Multiplatform applications.
  It contains several subfolders:
  - `commonMain` is for code that’s common for all targets.
  - Other folders are for Kotlin code that will be compiled for only the platform indicated in the folder name.
    For example, if you want to use Apple’s CoreCrypto for the iOS part of your Kotlin app,
    `iosMain` would be the right folder for such calls.

* `/iosApp` contains iOS applications. Even if you’re sharing your UI with Compose Multiplatform, 
  you need this entry point for your iOS app. This is also where you should add SwiftUI code for your project.


Learn more about [Kotlin Multiplatform](https://www.jetbrains.com/help/kotlin-multiplatform-dev/get-started.html)…

# Compose multiplatform with shared viewmodel

- App show how to share viewmodel between all platforms like Android and IOS.
- App use Koin dependency injection.
  
- [SharedViewModel.webm](https://github.com/HusseinKamal/SharedViewModelComposeMultiplatform/assets/29864161/d3b027fb-5764-4456-8676-6c6ca40e64b1)
