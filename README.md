# TO-DO Notes - Mobile HW5 Testing Assignment
============================================================================

This project is a homework assignment for Advanced Android in Kotlin 05.1: Testing Basics.

## Overview

TO-DO Notes is a task management application that allows users to:
- Create tasks
- Display tasks in a list
- Mark tasks as completed or active
- Filter tasks by their status
- Delete one or all tasks

## Project Structure

This project demonstrates various testing techniques for Android applications:
- Local unit tests for ViewModels and repositories
- Integration tests for database operations
- UI tests using Espresso

## Testing Features

This assignment covers:
- Creating and running local JUnit tests
- Testing LiveData and coroutines 
- Using test doubles (fakes, mocks)
- Implementing UI tests with Espresso

## Getting Started

1. Clone the repository
2. Open the project in Android Studio
3. Run the app to explore its functionality
4. Examine and run the tests in both test directories:
   - `src/test/` for unit tests
   - `src/androidTest/` for instrumented tests

## Reference Materials

This project is based on the following codelabs:
* [Testing Basics](https://codelabs.developers.google.com/codelabs/advanced-android-kotlin-training-testing-basics)
* [Introduction to Test Doubles and Dependency Injection](https://codelabs.developers.google.com/codelabs/advanced-android-kotlin-training-testing-test-doubles)
* [Survey of Testing Topics](https://codelabs.developers.google.com/codelabs/advanced-android-kotlin-training-testing-survey)

## Pre-requisites

You should be familiar with:

* The Kotlin programming language, including [Kotlin coroutines](https://developer.android.com/kotlin/coroutines) and their interaction with [Android Jetpack components](https://developer.android.com/topic/libraries/architecture/coroutines).
* The following core Android Jetpack libraries: [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel),
 [LiveData](https://developer.android.com/topic/libraries/architecture/livedata),
  [Navigation Component](https://developer.android.com/guide/navigation) and 
  [Data Binding](https://developer.android.com/topic/libraries/data-binding).
* Application architecture, following the pattern from the [Guide to app architecture](https://developer.android.com/jetpack/docs/guide).

## License

Copyright 2019 Google, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.
