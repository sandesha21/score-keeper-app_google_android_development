# Technology Stack

## Build System
- **Gradle**: Android Gradle Plugin 4.1.3 (updated from 3.5.0)
- **Gradle Wrapper**: 6.8.3 (updated from 5.4.1)
- **Build Tool**: Gradle Wrapper (gradlew/gradlew.bat)

## Java Compatibility
- **Working Configuration**: Java 21 with module system workarounds
- **JVM Arguments**: Added extensive --add-opens flags in gradle.properties
- **Java Source/Target**: Updated to Java 8 (from Java 7)
- **Status**: ✅ Build successful with current configuration

## Android Configuration
- **Compile SDK**: 28 (Android 9.0 API level 28)
- **Min SDK**: 15 (Android 4.0.3)
- **Target SDK**: 28
- **Package**: `com.example.android.trackcricketscore`

## Dependencies
- **AppCompat**: `com.android.support:appcompat-v7:28.0.0`
- **Constraint Layout**: `com.android.support.constraint:constraint-layout:1.1.3`
- **Testing**: JUnit 4.12, Espresso 3.0.2, Android Test Runner 1.0.2

## Common Commands
```bash
# Set Java 11 first
export JAVA_HOME=/opt/homebrew/opt/openjdk@11/libexec/openjdk.jdk/Contents/Home

# Build the project
./gradlew build

# Clean build artifacts
./gradlew clean

# Install debug APK
./gradlew installDebug

# Run unit tests
./gradlew test

# Run instrumented tests
./gradlew connectedAndroidTest
```

## Key Technologies
- **Language**: Java
- **UI Framework**: Android Views with XML layouts
- **Architecture**: Single Activity with direct view manipulation
- **Support Library**: Android Support Library (pre-AndroidX)