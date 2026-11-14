# Awesome Android with stars

[<img src="https://raw.githubusercontent.com/jstumpp/awesome-android/main/awesome-android.png">](https://github.com/jstumpp/awesome-android)

<p align="center">
  <a href="https://github.com/sindresorhus/awesome"><img alt="awesome" src="https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" /></a>
  <a href="https://github.com/JStumpp/awesome-android/actions/workflows/awesome-lint.yml"><img alt="Awesome Lint" src="https://github.com/JStumpp/awesome-android/actions/workflows/awesome-lint.yml/badge.svg" /></a>
  <img alt="PRs Welcome" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" />
</p>

A curated list of awesome Android libraries and resources. For general Java libraries have a look at [awesome-java](https://github.com/akullpp/awesome-java) ⭐ 49,532 | 🐛 42 | 📅 2026-09-23.

Awesome-Android is an amazing list for people who need a certain feature on their app, so the best ways to use are:

* Simply press <kbd>Ctrl</kbd> + <kbd>F</kbd> (or <kbd>⌘</kbd> + <kbd>F</kbd> on macOS) to search for a keyword
* Go through our Content Menu

## Contents

* [Emulators](#emulators)
* [Libraries](#libraries)
  * [Jetpack Compose](#jetpack-compose)
  * [Architecture](#architecture)
  * [Charts](#charts)
  * [Data binding](#data-binding)
  * [Dependency Injection](#dependency-injection)
  * [Game Development](#game-development)
  * [Security](#security)
  * [GUI](#gui)
  * [JSON](#json)
  * [Crash monitoring](#crash-monitoring)
  * [Networking](#networking)
  * [Logger](#logger)
  * [Database](#database)
  * [Testing](#testing)
  * [Tracking](#tracking)
  * [Maps](#maps)
  * [Utility](#utility)
  * [Debugging Tools](#debugging-tools)
  * [Wireless](#wireless)
  * [Chat & Messaging](#chat--messaging)
  * [Date & Time](#date--time)
  * [Payments](#payments)
  * [Google Play](#google-play)
  * [Code Quality](#code-quality)
  * [Other](#other)
* [Resources](#resources)
  * [Code examples](#code-examples)
  * [Podcasts](#podcasts)
  * [More lists of libraries](#more-lists-of-libraries)
* [Development Alternatives](#development-alternatives)
  * [Cross-Platform](#cross-platform)
  * [Kotlin Multiplatform](#kotlin-multiplatform)
* [Build & Performance](#build--performance)
* [Other Awesome Lists](#other-awesome-lists)

## Emulators

* [Android Emulator](https://developer.android.com/studio/run/emulator) - Official Android emulator integrated into Android Studio.
* [Genymotion](https://www.genymotion.com) - Fast Android emulator for app testing and development. *Commercial*

## Libraries

### Jetpack Compose

* [Jetpack Compose](https://developer.android.com/compose) - Modern toolkit for building native Android UI with declarative Kotlin APIs and Material 3 support.

### Architecture

* [Decompose](https://github.com/arkivanov/Decompose) ⭐ 2,890 | 🐛 4 | 🌐 Kotlin | 📅 2026-11-12 - Kotlin Multiplatform library for breaking down your code into lifecycle-aware business logic components.
* [Circuit](https://github.com/slackhq/circuit) ⭐ 1,860 | 🐛 16 | 🌐 Kotlin | 📅 2026-11-14 - Modern architecture framework for building Android apps with Compose.

### Charts

* [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) ⭐ 38,187 | 🐛 1 | 🌐 Kotlin | 📅 2026-10-09 - An Android chart and graph library supporting scaling and dragging by gesture.
* [Vico](https://github.com/patrykandpatrick/vico) ⭐ 3,206 | 🐛 5 | 🌐 Kotlin | 📅 2026-11-13 - Modern chart library with support for both Jetpack Compose and Android Views.

### Data binding

* [Data Binding Library](https://developer.android.com/topic/libraries/data-binding/) - Official Android Data Binding Library to write declarative layouts and minimize the glue code necessary to bind application logic and layouts.

### Dependency Injection

* [Dagger 2](https://github.com/google/dagger) ⭐ 17,690 | 🐛 368 | 🌐 Java | 📅 2026-11-13 - A fast dependency injector for Android and Java.
* [Hilt](https://developer.android.com/training/dependency-injection/hilt-android) - Official dependency injection library built on top of Dagger for Android.
* [Koin](https://insert-koin.io/) - Lightweight dependency injection framework for Kotlin.

### Game Development

* [Godot](https://github.com/godotengine/godot) ⭐ 120,124 | 🐛 19,047 | 🌐 C++ | 📅 2026-11-13 - Cross-platform 2/3D game engine with an IDE and under MIT license.
* [Libgdx](https://libgdx.com/) - Cross-platform game engine and SDK. [Open Source](https://github.com/libgdx/libgdx) ⭐ 25,526 | 🐛 333 | 🌐 Java | 📅 2026-11-14
* [Vuforia](https://www.ptc.com/en/products/vuforia) - Augmented Reality library. *Commercial*
* [Unity](https://unity.com/features/multiplatform) - Cross-platform game creation system. *Commercial*

### Security

* [Google Tink](https://github.com/tink-crypto/tink-java) ⭐ 315 | 🐛 15 | 🌐 Java | 📅 2026-11-13 - Multi-language cross-platform cryptography library providing secure APIs for common cryptographic tasks.

### GUI

* [Lottie](https://github.com/airbnb/lottie-android) ⭐ 35,771 | 🐛 84 | 🌐 Java | 📅 2026-02-15 - Library for rendering After Effects animations natively on Android.
* [Glide](https://github.com/bumptech/glide) ⭐ 35,011 | 🐛 688 | 🌐 Java | 📅 2026-11-14 - An image loading and caching library for Android focused on smooth scrolling, Recommended by Google.
* [Material Components for Android](https://github.com/material-components/material-components-android) ⭐ 17,455 | 🐛 805 | 🌐 Java | 📅 2026-10-16 - Modular and customizable Material Design UI components for Android.
* [Fresco](https://github.com/meta/fresco) ⭐ 17,163 | 🐛 265 | 🌐 Kotlin | 📅 2026-11-13 - An Android library for managing images and the memory they use.
* [Android View Animations](https://github.com/daimajia/AndroidViewAnimations) ⭐ 12,430 | 🐛 69 | 🌐 Java | 📅 2021-08-18 - Cute view animation collection.
* [Coil](https://github.com/coil-kt/coil) ⭐ 11,959 | 🐛 63 | 🌐 Kotlin | 📅 2026-11-14 - Image loading for Android backed by Kotlin Coroutines.
* [MaterialDrawer](https://github.com/mikepenz/MaterialDrawer) ⭐ 11,640 | 🐛 10 | 🌐 Kotlin | 📅 2026-11-09 - Simple take on a material design navigation drawer.
* [AppIntro](https://github.com/AppIntro/AppIntro) ⭐ 10,565 | 🐛 42 | 🌐 Kotlin | 📅 2026-11-11 - Library for creating beautiful intro slides for your app.
* [Litho (By Meta)](https://github.com/meta/litho) ⭐ 7,809 | 🐛 118 | 🌐 Kotlin | 📅 2026-11-13 - A declarative framework for building efficient UIs on Android.
* [Compressor](https://github.com/zetbaitsu/Compressor) ⭐ 7,229 | 🐛 140 | 🌐 Kotlin | 📅 2026-03-05 - Lightweight and powerful Android image compression library.
* [TapTargetView](https://github.com/KeepSafe/TapTargetView) ⭐ 5,458 | 🐛 58 | 🌐 Java | 📅 2024-10-08 - An implementation of tap targets from the Material Design guidelines for feature discovery.
* [Material Dots Indicators](https://github.com/tommybuonomo/dotsindicator) ⭐ 3,608 | 🐛 7 | 🌐 Kotlin | 📅 2026-10-11 - Three Material Dots Indicators styles for View Pagers.
* [Media3 (ExoPlayer)](https://github.com/androidx/media) ⭐ 3,075 | 🐛 947 | 🌐 Java | 📅 2026-11-13 - Jetpack Media3 support libraries for media use cases, including ExoPlayer, an extensible media player for Android.
* [Navigation](https://developer.android.com/guide/navigation) - Framework for building in-app navigation with type-safe argument passing.
* [Pull to refresh](https://developer.android.com/reference/androidx/swiperefreshlayout/widget/SwipeRefreshLayout) - A swipe refresh layout is available in AndroidX.
* [CameraX](https://developer.android.com/training/camerax) - Jetpack library that makes camera app development easier with consistent API across devices.

### JSON

* [Gson](https://github.com/google/gson) ⭐ 24,231 | 🐛 339 | 🌐 Java | 📅 2026-11-13 - Java library used for serializing and deserializing Java objects from and into JSON.
* [Moshi](https://github.com/square/moshi) ⭐ 10,164 | 🐛 115 | 🌐 Kotlin | 📅 2026-11-13 - A modern JSON library for Android and Java.
* [Jackson JSON Processor](https://github.com/FasterXML/jackson) ⭐ 9,836 | 🐛 1 | 📅 2026-11-09 - High-performance JSON processor.
* [kotlinx.serialization](https://github.com/Kotlin/kotlinx.serialization) ⭐ 5,955 | 🐛 311 | 🌐 Kotlin | 📅 2026-11-13 - Kotlin multiplatform serialization library with JSON support.

### Crash monitoring

* [Measure](https://github.com/measure-sh/measure/) ⭐ 1,445 | 🐛 78 | 🌐 TypeScript | 📅 2026-11-14 - Open source tool to monitor crashes, ANRs, and performance of mobile apps. Can be self-hosted.
* [Sentry Android](https://github.com/getsentry/sentry-java) ⭐ 1,362 | 🐛 316 | 🌐 Kotlin | 📅 2026-11-13 - Open source error tracking with real-time crash reporting. *Commercial (has free tier)*
* [Bugsnag](https://www.bugsnag.com/) - Cross platform error monitoring. Free tier. Support for SDK & NDK. Error reports include data on device, release, user, and allows arbitrary data. *Commercial*
* [Firebase Crashlytics](https://firebase.google.com/products/crashlytics) - Easy crash reporting solution. *Commercial (has free tier)*

### Networking

* [OkHttp](https://github.com/lysine-dev/okhttp) ⭐ 47,112 | 🐛 169 | 🌐 Kotlin | 📅 2026-11-14 - An HTTP+SPDY client for Android and Java applications (continued project).
* [Retrofit](https://github.com/lysine-dev/retrofit) ⭐ 43,938 | 🐛 148 | 🌐 Java | 📅 2026-11-14 - Turns your REST API into a Java interface (continued project).
* [Ktor Client](https://github.com/ktorio/ktor) ⭐ 14,566 | 🐛 130 | 🌐 Kotlin | 📅 2026-11-13 - Asynchronous HTTP client for Kotlin with multiplatform support.
* [Fast-Android-Networking](https://github.com/amitshekhariitbhu/Fast-Android-Networking) ⭐ 5,937 | 🐛 235 | 🌐 Java | 📅 2026-02-05 - A Complete Fast Android Networking Library that also support HTTP/2.
* [Apollo Kotlin](https://github.com/apollographql/apollo-kotlin) ⭐ 3,976 | 🐛 110 | 🌐 Kotlin | 📅 2026-11-12 - Strongly-typed GraphQL client for Kotlin and Java.
* [Android Volley](https://google.github.io/volley/) - Official Android HTTP library that makes networking for easier and faster.

### Logger

* [logger](https://github.com/orhanobut/logger) ⭐ 13,827 | 🐛 81 | 🌐 Kotlin | 📅 2026-10-03 - Simple, pretty and powerful logger for Android.
* [timber](https://github.com/JakeWharton/timber) ⭐ 10,857 | 🐛 63 | 🌐 Kotlin | 📅 2026-11-13 - A logger with a small, extensible API which provides utility on top of Android's normal Log class.
* [LoggingInterceptor](https://github.com/ihsanbal/LoggingInterceptor) ⭐ 1,362 | 🐛 1 | 🌐 Kotlin | 📅 2026-02-19 - An OkHttp interceptor which pretty logs request and response data.
* [Logback Android](https://github.com/tony19/logback-android) ⭐ 1,265 | 🐛 12 | 🌐 Java | 📅 2026-11-10 - Logback port to Android which provides a highly configurable logging framework for Android apps.
* [Kermit](https://github.com/touchlab/Kermit) ⭐ 1,044 | 🐛 8 | 🌐 Kotlin | 📅 2026-11-12 - Kotlin Multiplatform logging library with support for multiple platforms.

### Database

* [SQLDelight](https://github.com/sqldelight/sqldelight) ⭐ 6,906 | 🐛 374 | 🌐 Kotlin | 📅 2026-11-12 - Generates typesafe Kotlin APIs from SQL statements with Kotlin Multiplatform support.
* [DBFlow](https://github.com/agrosner/DBFlow) ⭐ 4,842 | 🐛 48 | 🌐 Kotlin | 📅 2026-08-23 - Fast and powerful ORM with compile-time annotation processing.
* [ObjectBox](https://github.com/objectbox/objectbox-java) ⭐ 4,629 | 🐛 146 | 🌐 Java | 📅 2026-10-20 - Simple but powerful object database, optimized for performance & mobile.
* [requery](https://github.com/requery/requery) ⭐ 3,123 | 🐛 170 | 🌐 Java | 📅 2026-02-09 - Compile time ORM and SQL query library for Java & Android.
* [DbInspector](https://github.com/infinum/android_dbinspector) ⭐ 955 | 🐛 7 | 🌐 Kotlin | 📅 2026-11-01 - Provides a simple way to view the contents of the in-app database for debugging purposes.
* [Nitrite Database](https://github.com/nitrite/nitrite-java) ⭐ 923 | 🐛 0 | 🌐 Java | 📅 2026-11-12 - A NoSQL embedded document store for Android with MongoDB like API.
* [Room](https://developer.android.com/training/data-storage/room) - Official SQLite object mapping library with compile-time verification of SQL queries.

### Testing

* [Maestro](https://github.com/mobile-dev-inc/maestro) ⭐ 16,403 | 🐛 453 | 🌐 Kotlin | 📅 2026-11-13 - Mobile UI testing framework for end-to-end testing with simple YAML-based syntax.
* [MockK](https://github.com/mockk/mockk) ⭐ 5,769 | 🐛 263 | 🌐 Kotlin | 📅 2026-11-14 - Mocking library for Kotlin with natural syntax and comprehensive DSL.
* [Kotest](https://github.com/kotest/kotest) ⭐ 4,790 | 🐛 47 | 🌐 Kotlin | 📅 2026-11-14 - Flexible and comprehensive testing framework for Kotlin with multiple testing styles.
* [Turbine](https://github.com/cashapp/turbine) ⭐ 2,874 | 🐛 18 | 🌐 Kotlin | 📅 2026-11-11 - Testing library for Kotlin Flows with simple and expressive assertions.
* [Paparazzi](https://github.com/cashapp/paparazzi) ⭐ 2,640 | 🐛 195 | 🌐 Kotlin | 📅 2026-11-13 - Render Android screens as images for snapshot testing without a device or emulator.
* [AndroidX Test](https://github.com/android/android-test) ⭐ 1,229 | 🐛 244 | 🌐 Java | 📅 2026-11-12 - Testing libraries for Android including JUnit rules and Espresso APIs.
* [Roborazzi](https://github.com/takahirom/roborazzi) ⭐ 1,082 | 🐛 149 | 🌐 Kotlin | 📅 2026-11-13 - Screenshot testing library for Android using Robolectric.
* [Droidline](https://github.com/KnifeLemon/Droidline) ⭐ 538 | 🐛 0 | 🌐 Go | 📅 2026-11-03 - Automate real Android phones from Python, Node.js, C# or a CLI over Wi-Fi, without ADB or root.
* [Ghost in the Droid](https://github.com/ghost-in-the-droid/android-agent) ⭐ 421 | 🐛 3 | 🌐 Python | 📅 2026-08-13 - Python MCP server for AI agent control of Android and iOS devices via ADB and WebDriverAgent.
* [Espresso](https://developer.android.com/training/testing/espresso) - Official Android UI testing framework for writing reliable UI tests.
* [Roboletric](https://robolectric.org/) - Unit test framework to run tests inside the JVM on your workstation, not in the emulator.

### Tracking

* [Countly](https://countly.com/) - Open source mobile & web analytics, push notifications and crash reporting platform, based on Node.js, MongoDB and Linux.
* [Mixpanel](https://mixpanel.com/) - Analytics platform to analyze the users. *Commercial*

### Maps

* [android-maps-utils](https://github.com/googlemaps/android-maps-utils) ⭐ 3,625 | 🐛 33 | 🌐 Kotlin | 📅 2026-11-13 - Utility library for Google Maps Android API with features like marker clustering and heat maps.
* [Maps Compose](https://github.com/googlemaps/android-maps-compose) ⭐ 1,319 | 🐛 92 | 🌐 Kotlin | 📅 2026-11-13 - Jetpack Compose components for Google Maps.

### Utility

* [LeakCanary](https://github.com/square/leakcanary) ⭐ 30,009 | 🐛 132 | 🌐 Kotlin | 📅 2026-10-21 - Catch memory leaks as they occur.
* [Byte Buddy](https://bytebuddy.net) - Runtime code generation library with support for Android.

### Debugging Tools

* [Android Debug Bridge - ADB](https://github.com/mzlogin/awesome-adb/blob/master/README.en.md) ⭐ 12,542 | 🐛 53 | 📅 2026-09-29 - A command-line tool to assist in debugging Android-powered devices.
* [Android Debug Database](https://github.com/amitshekhariitbhu/Android-Debug-Database) ⭐ 8,710 | 🐛 83 | 🌐 Java | 📅 2026-02-05 - Powerful library for debugging databases and shared preferences in Android applications.
* [Pidcat](https://github.com/JakeWharton/pidcat) ⭐ 4,953 | 🐛 67 | 🌐 Python | 📅 2024-05-10 - A colored command-line ADB wrapper that only shows log entries for a specific application package.
* [Chucker](https://github.com/ChuckerTeam/chucker) ⭐ 4,588 | 🐛 83 | 🌐 Kotlin | 📅 2026-11-14 - An HTTP inspector for Android & OkHTTP (like Charles but on device).
* [ADB Enhanced](https://github.com/ashishb/adb-enhanced) ⭐ 1,401 | 🐛 2 | 🌐 Python | 📅 2026-11-12 - A command-line wrapper around ADB for developers, so that, developers don't have to remember esoteric version-dependent commands.
* [Linx](https://github.com/pedrovgs/Lynx) ⭐ 789 | 🐛 9 | 🌐 Java | 📅 2026-01-16 - Show logcat inside the device for debug builds.
* [handsets](https://github.com/elliotgao2/handsets) ⭐ 122 | 🐛 3 | 🌐 Rust | 📅 2026-06-01 - Android control CLI that drives devices over ADB with no APK required.

### Wireless

* [Nordic Android-BLE-Library](https://github.com/NordicSemiconductor/Android-BLE-Library) ⭐ 2,429 | 🐛 59 | 🌐 Java | 📅 2026-10-13 - Android BLE library from Nordic Semiconductor for reliable BLE communication.
* [Kable](https://github.com/JuulLabs/kable) ⭐ 1,205 | 🐛 84 | 🌐 Kotlin | 📅 2026-11-12 - Kotlin Asynchronous Bluetooth Low Energy library for Android and other platforms.

### Chat & Messaging

* [Stream Chat](https://getstream.io/chat/sdk/android/tutorial/compose/) - Comprehensive SDK & Components for real-time chat, powered by [Stream](https://getstream.io/chat/). *Commercial*

### Date & Time

* [kotlinx-datetime](https://github.com/Kotlin/kotlinx-datetime) ⭐ 2,824 | 🐛 44 | 🌐 Kotlin | 📅 2026-11-12 - A multiplatform Kotlin library for working with date and time.

### Payments

* [Square In-App Payments for Android](https://developer.squareup.com/docs/in-app-payments-sdk/build-on-android) - Integrate Square payments into your mobile app with Digital wallet and stored card support for quick checkout. *Commercial*

### Google Play

* [Google Play Billing](https://developer.android.com/google/play/billing) - Official library for in-app purchases and subscriptions on Google Play.
* [In-App Updates](https://developer.android.com/guide/playcore/in-app-updates) - Keep your app up to date with flexible and immediate in-app update flows.
* [In-App Review](https://developer.android.com/guide/playcore/in-app-review) - Prompt users to submit Play Store ratings and reviews without leaving your app.

### Code Quality

* [Detekt](https://github.com/detekt/detekt) ⭐ 7,118 | 🐛 167 | 🌐 Kotlin | 📅 2026-11-14 - Static code analysis tool for Kotlin with over 200 built-in rules.
* [ktlint](https://github.com/ktlint/ktlint) ⭐ 6,776 | 🐛 16 | 🌐 Kotlin | 📅 2026-11-10 - Anti-bikeshedding Kotlin linter with built-in formatter.
* [Spotless](https://github.com/diffplug/spotless) ⭐ 5,729 | 🐛 253 | 🌐 Java | 📅 2026-11-10 - Code formatter that supports multiple languages and can enforce consistent formatting in builds.

### Other

* [Guava: Google Core Libraries for Java](https://github.com/google/guava) ⭐ 51,924 | 🐛 768 | 🌐 Java | 📅 2026-11-13 - Collections, caching, primitives support, concurrency libraries, common annotations, string processing, I/O, and so forth.
* [RxJava](https://github.com/ReactiveX/RxJava) ⭐ 48,153 | 🐛 13 | 🌐 Java | 📅 2026-11-10 - Reactive Extensions for the JVM – a library for composing asynchronous and event-based programs using observable sequences for the Java VM.
* [RxAndroid](https://github.com/ReactiveX/RxAndroid) ⭐ 19,893 | 🐛 1 | 🌐 Java | 📅 2026-11-02 - Adds minimum RxJava bindings for easy writing of reactive Android java code.
* [Kotlin Coroutines](https://github.com/Kotlin/kotlinx.coroutines) ⭐ 13,820 | 🐛 350 | 🌐 Kotlin | 📅 2026-11-12 - Library for asynchronous programming with coroutines and Flow for reactive streams.
* [Arrow](https://github.com/arrow-kt/arrow) ⭐ 6,589 | 🐛 35 | 🌐 Kotlin | 📅 2026-11-14 - Functional companion to Kotlin's Standard Library with typed functional programming support.
* [AboutLibraries](https://github.com/mikepenz/AboutLibraries) ⭐ 4,498 | 🐛 6 | 🌐 Kotlin | 📅 2026-11-14 - Automatically generates an About this app section, with a list of used libraries.
* [KSP](https://github.com/google/ksp) ⭐ 3,485 | 🐛 165 | 🌐 Kotlin | 📅 2026-11-13 - Kotlin Symbol Processing API for writing lightweight compiler plugins with better performance than kapt.
* [refreshVersions](https://github.com/Splitties/refreshVersions) ⭐ 1,709 | 🐛 129 | 🌐 Kotlin | 📅 2025-08-16 - A Kotlin dsl to simplify dependencies management.
* [Licensee](https://github.com/cashapp/licensee) ⭐ 757 | 🐛 32 | 🌐 Kotlin | 📅 2026-11-11 - Gradle plugin which validates the licenses of your dependency graph match what you expect, or it fails your build!
* [AndroidX](https://developer.android.com/jetpack/androidx) - The modern Android development toolkit that replaces the Android Support Library, providing backward-compatible versions of Android framework APIs.
* [WorkManager](https://developer.android.com/topic/libraries/architecture/workmanager) - Schedule deferrable and guaranteed background work with a flexible API.
* [Paging](https://developer.android.com/topic/libraries/architecture/paging/v3-overview) - Load and display pages of data from a larger dataset with efficient memory usage.
* [DataStore](https://developer.android.com/topic/libraries/architecture/datastore) - Modern data storage solution using Kotlin coroutines and Flow to replace SharedPreferences.
* [Google Play Services](https://developers.google.com/android/guides/overview) - Library to access Google services, such as account syncing, Google+ (sharing, single sign-on), Google Maps, Location APIs, Google Play Games, Cloud Messaging, Android Device Manager, and others.
* [ML Kit](https://developers.google.com/ml-kit) - Mobile SDK for machine learning tasks like barcode scanning, text recognition, and face detection.
* [Google Code Scanner](https://developers.google.com/ml-kit/vision/barcode-scanning/code-scanner) - High-quality barcode scanning without requiring app permissions using Google Play Services.

## Resources

* [Android Tips & Tricks](https://github.com/nisrulz/android-tips-tricks) ⭐ 4,745 | 🐛 2 | 🌐 Python | 📅 2026-11-11 - Cheatsheet about tips and tricks for Android Development.
* [Programming Community Curated Resources for Learning Android Development](https://hackr.io/tutorials/learn-android-development) - Android Tutorials & Courses submitted and voted by the programming community.
* [Vogella Tutorials](https://www.vogella.com/tutorials/android.html) - Very good tutorials by Lars Vogel.
* [Android API Levels](https://apilevels.com/) - A quick reference table of Android versions with SDK & API levels, version codes, codenames, cumulative usage, and more.
* [Android Hive Tutorials](https://www.androidhive.info) - Very good tutorials for beginners.
* [Android Weekly](https://androidweekly.net) - Newsletter with weekly information about Android.
* [Android Asset Studio](https://romannurik.github.io/AndroidAssetStudio/) - Generator for icons and other assets.
* [Device Art Generator](https://developer.android.com/distribute/marketing-tools/device-art-generator) - Wraps app screenshots in real device artwork.
* [Pencil Project](https://pencil.evolus.vn/) - An open source prototyping software.
* [Future Studio](https://futurestud.io/tutorials/tag/android) - Extensive Android tutorials on Retrofit, Glide & Gson.
* [Google Developers Training](https://developer.android.com/courses/) -  Google Developers Official Training page has list of various useful learning resources for beginner as well seasoned developer.
* [Mindorks](https://mindorks.com/) - Become a complete and happy Android developer.
* [AndroidVille](https://ayusch.com/) - Become a better Android Engineer. A website dedicated to Android Development covering advanced topics such as RxJava, Android Zygote and much more.
* [Android Stack Weekly](https://canopas.com/tagged/canopas-android-weekly) - A weekly newsletter on new development and updates of Android universe.
* [Roadmap.sh Android Roadmap](https://roadmap.sh/android) - Community-created Android developer roadmap.

### Code examples

* [Android Architecture Blueprints](https://github.com/android/architecture-samples) ⭐ 45,901 | 🐛 228 | 🌐 Kotlin | 📅 2026-11-14 - The Android Architecture Blueprints project demonstrates strategies to help solve or avoid common Android problems.
* [Compose Samples](https://github.com/android/compose-samples) ⭐ 23,556 | 🐛 10 | 🌐 Kotlin | 📅 2026-11-09 - Official sample apps showcasing Jetpack Compose UI toolkit.
* [Now in Android](https://github.com/android/nowinandroid) ⭐ 22,079 | 🐛 281 | 🌐 Kotlin | 📅 2026-11-14 - Official sample app demonstrating modern Android development best practices.

### Podcasts

* [Fragmented](https://fragmentedpodcast.com/) - Is the Android developer podcast where Donn Felker and Kaushik Gopal talk about building good software and becoming better Android developers.
* [Android Developers Backstage](https://androidbackstage.blogspot.com/) - Is a podcast by and for Android developers. Hosted by developers from the Android engineering team, this show covers topics of interest to Android programmers, with in-depth discussions and interviews with engineers on the Android team at Google.
* [Android Dialogs](https://www.youtube.com/channel/UCMEmNnHT69aZuaOrE-dF6ug/feed) - Is a video based podcast, where they have bite-sized conversations with people from the Android community.
* [Talking Kotlin](https://talkingkotlin.com/) - A Podcast on Kotlin and more.
* [Android Authority](https://www.androidauthority.com/podcast/) - Is a weekly Android podcast hosted by Adam Doud, Joe Hindy, and Jonathan Feist from the Android Authority team.

### More lists of libraries

* [Square libraries](https://square.github.io/) - Multiple high quality libraries by square.
* [Awesome Android @LibHunt](https://android.libhunt.com) - Your go-to Android Toolbox.
* [Android Store](https://mindorks.com/android/store) - Search Android Libraries, Projects, and Tools.

## Development Alternatives

My personal recommendation is (for now) to use the Android SDK to build a native app. Scala and Kotlin are both options; multidex requirements depend on an app's method-reference count and minimum SDK level, not its language. Cross-platform alternatives can also be useful when they fit a project's requirements.

### Cross-Platform

* [React Native](https://github.com/react/react-native) ⭐ 126,919 | 🐛 1,406 | 🌐 C++ | 📅 2026-11-14 - A framework for building native apps with React.
* [.NET MAUI](https://github.com/dotnet/maui) ⭐ 23,321 | 🐛 1,353 | 🌐 C# | 📅 2026-11-14 - .NET Multi-platform App UI, the evolution of Xamarin.Forms, for building native cross-platform apps with .NET and C#.
* [Kivy](https://github.com/kivy/kivy) ⭐ 19,028 | 🐛 896 | 🌐 Python | 📅 2026-11-13 - Open source Python framework for Android apps, packaged with Buildozer.
* [Flet](https://github.com/flet-dev/flet) ⭐ 17,554 | 🐛 211 | 🌐 Python | 📅 2026-11-14 - Build Flutter apps using Python.
* [Capacitor](https://github.com/ionic-team/capacitor) ⭐ 17,085 | 🐛 145 | 🌐 TypeScript | 📅 2026-11-13 - Build cross-platform Native Progressive Web Apps for iOS, Android, and the web. Very promising Cordova alternative.
* [BeeWare](https://github.com/beeware/toga) ⭐ 5,429 | 🐛 325 | 🌐 Python | 📅 2026-11-13 - Write native Android apps in Python using Toga and Briefcase.
* [Apache Cordova](https://github.com/apache/cordova-android) ⭐ 3,794 | 🐛 102 | 🌐 JavaScript | 📅 2026-11-13 - Cordova based applications are, at the core, applications written with web technology: HTML, CSS and JavaScript.
* [Solar2D](https://github.com/coronalabs/corona) ⭐ 2,904 | 🐛 202 | 🌐 C++ | 📅 2026-11-09 - Cross-platform framework for creating 2D games and apps (formerly Corona SDK).
* [Flutter](https://flutter.dev/) - Google's mobile app SDK for high-quality native interfaces for Android and iOS in very quick time.
* [NativeScript](https://nativescript.org/) - An open-source framework to build native iOS and Android apps with JavaScript from a single code base.
* [Ionic Framework](https://ionicframework.com) - A framework to build hybrid apps with mobile-optimized HTML, CSS and JS with AngularJS.

### Kotlin Multiplatform

* [Compose Multiplatform](https://github.com/JetBrains/compose-multiplatform) ⭐ 19,487 | 🐛 26 | 🌐 Kotlin | 📅 2026-11-13 - Jetpack Compose for iOS, Desktop, and Web built on Kotlin Multiplatform.
* [KuiklyUI](https://github.com/Tencent-TDS/KuiklyUI) ⭐ 3,637 | 🐛 147 | 🌐 Kotlin | 📅 2026-11-13 - Kotlin Multiplatform UI framework supporting Android, iOS, and other platforms.
* [Kotlin coding challenges](https://github.com/igorwojda/kotlin-coding-challenges) ⭐ 1,054 | 🐛 1 | 🌐 Kotlin | 📅 2026-11-10 - Set of programming challenges thats helps to improve whiteboard coding and problem-solving skills.

## Build & Performance

* [R8](https://developer.android.com/topic/performance/app-optimization/enable-app-optimization) - Default code shrinker and optimizer for Android apps.
* [ProGuard](https://www.guardsquare.com/proguard) - Open-source Java bytecode optimizer and shrinker for Android apps.
* [ProGuard Playground](https://playground.proguard.com/) - Interactive online tool for visualizing and testing ProGuard and R8 keep rules.
* [Booster](https://github.com/didi/booster) ⭐ 5,075 | 🐛 52 | 🌐 Kotlin | 📅 2026-11-05 - An optimization toolkit for Android applications.

## Other Awesome Lists

Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) ⭐ 33,787 | 🐛 66 | 🌐 Ruby | 📅 2024-06-02 list.

## Contributing

Your contributions are always welcome! Please read the [contribution guidelines](contributing.md) first.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-11-14._
