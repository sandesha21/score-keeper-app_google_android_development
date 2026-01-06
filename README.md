# Track Cricket Score

A simple Android application for tracking cricket match scores between two teams. Built as part of the Android Basics Nanodegree (ABND) Project 2.

## Features

- **Score Tracking**: Track runs for both teams (1, 2, 3, 4, 6 runs)
- **Wicket Management**: Track wickets fallen (maximum 10 per team)
- **Reset Functionality**: Start fresh matches with a single tap
- **Real-time Updates**: Instant score display updates
- **Cricket-specific Logic**: Prevents adding wickets beyond 10 (all out)

## Screenshots

The app provides an intuitive interface for tracking cricket scores with dedicated buttons for common scoring scenarios.

## Technical Details

- **Language**: Java
- **Min SDK**: Android 4.0.3 (API 15)
- **Target SDK**: Android 9.0 (API 28)
- **Architecture**: Single Activity with direct view manipulation
- **UI Framework**: Android Views with XML layouts

## Getting Started

### Prerequisites
- Android Studio 3.5+
- Android SDK 28
- Java 8+

### Building the Project
```bash
# Clone the repository
git clone <repository-url>

# Build the project
./gradlew build

# Install on connected device
./gradlew installDebug
```

### Running Tests
```bash
# Run unit tests
./gradlew test

# Run instrumented tests
./gradlew connectedAndroidTest
```

## Project Structure

```
app/src/main/
├── java/com/example/android/trackcricketscore/
│   └── MainActivity.java          # Main activity with scoring logic
├── res/
│   ├── layout/                    # XML layout files
│   ├── drawable/                  # Images and icons
│   └── values/                    # Strings, colors, styles
└── AndroidManifest.xml            # App configuration
```

## Learning Objectives

This project demonstrates key Android development concepts:

- **Button Interactions**: Implementing onClick handlers for score updates
- **View Updates**: Dynamically updating TextViews with new scores
- **Variable Scoping**: Proper management of score and wicket variables
- **findViewById**: Locating and manipulating UI elements
- **Method Organization**: Clean separation of concerns in activity methods

## License

This project is part of the Android Basics Nanodegree program.