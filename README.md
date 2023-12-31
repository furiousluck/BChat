# BChat - Android Bluetooth Chat Application

BChat is an Android application that enables users to send text messages and images to other paired devices over Bluetooth. The app is built using Kotlin and utilizes Jetpack Compose for the user interface, Kotlin Flows for asynchronous data streaming, and Coroutines for handling concurrent tasks.

## Features

- Establish Bluetooth connections with other devices.
- Send and receive text messages over Bluetooth.
- Send and receive images over Bluetooth.
- Change device Bluetooth name.
- Toggle Bluetooth on/off within the app.
- Toggle Bluetooth discoverability within the app.
- Scan for new Bluetooth devices.
- Pair with new Bluetooth devices.
- Unpair already paired devices.
- Minimalistic and user-friendly UI using Jetpack Compose.
- Efficient data streaming and handling with Kotlin Flows and Coroutines.

## Video Demo
https://github.com/Pablit0x/BlueChat/assets/76017191/9321b7ae-4889-4dc7-b03c-68e6b73a16c7

## Requirements

- Android device with Bluetooth support or Emulator with support for Virtual Bluetooth.
- Android API level 33 or above.

## Getting Started

To get started with BlueChat, follow these steps:

1. Clone this repository to your local machine.

2. Open the project in Android Studio.

3. Build and run the application on your Android device or emulator.


## Libraries and Technologies Used

- Kotlin: Programming language used for app development.
- Jetpack Compose: Modern UI toolkit for building native Android UI.
- Kotlin Flows: Asynchronous data streaming for handling Bluetooth data.
- Coroutines: For managing concurrency and asynchronous tasks.
- Android Bluetooth API: For handling Bluetooth communication.
- Room: For persistent storage of messages in a local SQLite database.
- Dagger Hilt: For simple dependency injection, providing a clean and maintainable app architecture.
- Coil: For async image loading.
- Android Storage: For saving received images to the phone's internal storage.
- Android System Photo Picker: For allowing users to select images from their device's gallery.

