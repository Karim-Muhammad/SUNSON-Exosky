# Exosky - Explore Exoplanets

Welcome to Exosky, an educational app developed for the NASA Apps event. This app allows users to explore exoplanets with an interactive screen to connect between stars and others, providing information about exoplanets and commonly connected stars.

## Table of Contents

- [Exosky - Explore Exoplanets](#exosky---explore-exoplanets)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Features](#features)
  - [Project Structure](#project-structure)
  - [Installation](#installation)
    - [Prerequisites](#prerequisites)
    - [Steps](#steps)
      - [Android Native App](#android-native-app)
      - [Flutter App](#flutter-app)
  - [Usage](#usage)
  - [API](#api)
  - [Contributing](#contributing)
  - [License](#license)
  - [Acknowledgements](#acknowledgements)

## Introduction

Exosky is designed to be an engaging educational tool that helps users learn about exoplanets and their connections to stars. The app features an interactive star map where users can draw connections between stars and access detailed information about various exoplanets.

This project is part of the NASA Apps event, specifically for the Exosky challenge. For more details about the challenge, visit the [NASA Space Apps Challenge 2024 - Exosky](https://www.spaceappschallenge.org/nasa-space-apps-2024/challenges/exosky/?tab=details).

## Features

- **Interactive Star Map**: Draw connections between stars and explore the night sky.
- **Exoplanet Information**: Access detailed information about various exoplanets.
- **Educational Videos**: Watch educational videos about exoplanets and astronomy.
- **User-Friendly Interface**: Easy-to-use interface designed for all age groups.

## Project Structure

The project is divided into two main parts: a native Android app and a Flutter app.

## Installation

### Prerequisites

- Android Studio
- Flutter SDK
- Kotlin
- Gradle

### Steps

#### Android Native App

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/exosky.git
   ```

2. Navigate to the Android native app directory:

   ```sh
   cd AndroidNative/exosky-native-android
   ```

3. Open the project in Android Studio.

4. Build the project:

   ```sh
   ./gradlew build
   ```

5. Run the app on an emulator or a physical device.

#### Flutter App

1. Navigate to the Flutter app directory:

   ```sh
   cd Flutter/x_space
   ```

2. Get the Flutter dependencies:

   ```sh
   flutter pub get
   ```

3. Run the app:
   ```sh
   flutter run
   ```

## Usage

1. Launch the app.
2. Use the interactive star map to explore stars and draw connections.
3. Tap on stars to get detailed information about connected exoplanets.
4. Watch educational videos to learn more about exoplanets and astronomy.

## API

The app uses various APIs to fetch data about exoplanets and stars. Below are some of the key APIs used:

- [NASA Exoplanet Archive API](https://exoplanetarchive.ipac.caltech.edu/docs/program_interfaces.html)
- [Open Notify API](http://open-notify.org/Open-Notify-API/)

## Contributing

We welcome contributions from the community. To contribute:

1. Fork the repository.
2. Create a new branch:
   ```sh
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit them:
   ```sh
   git commit -m "Add your feature"
   ```
4. Push to the branch:
   ```sh
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- NASA for the inspiration and data.
- [Glide](https://github.com/bumptech/glide) for image loading.
- [PhotoView](https://github.com/Baseflow/PhotoView) for zoomable images.
- [OkHttp](https://square.github.io/okhttp/) for network requests.

---

Developed with ❤️ for the NASA Apps event.
