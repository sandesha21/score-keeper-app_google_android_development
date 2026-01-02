# Project Structure

## Standard Android Project Layout
```
TrackCricketScore/
├── app/                           # Main application module
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/android/trackcricketscore/
│   │   │   │   └── MainActivity.java    # Single activity handling all logic
│   │   │   ├── res/
│   │   │   │   ├── drawable/           # Images and drawable resources
│   │   │   │   ├── layout/             # XML layout files
│   │   │   │   ├── mipmap-*/           # App icons (various densities)
│   │   │   │   └── values/             # Strings, colors, styles
│   │   │   └── AndroidManifest.xml     # App configuration
│   │   ├── androidTest/               # Instrumented tests
│   │   └── test/                      # Unit tests
│   ├── build.gradle                   # Module-level build configuration
│   └── proguard-rules.pro            # ProGuard configuration
├── gradle/wrapper/                    # Gradle wrapper files
├── build.gradle                       # Project-level build configuration
├── settings.gradle                    # Project settings
└── gradlew[.bat]                     # Gradle wrapper scripts
```

## Code Organization Patterns
- **Single Activity Architecture**: All functionality in `MainActivity.java`
- **Method Naming**: Descriptive names like `addOneForTeamA()`, `displayForTeamA()`
- **Variable Naming**: Clear prefixes like `scoreTeamA`, `wicketsTeamB`
- **Resource IDs**: Snake case like `team_a_score`, `team_b_wicket`

## Package Structure
- **Main Package**: `com.example.android.trackcricketscore`
- **Single Activity**: All UI logic contained in `MainActivity`
- **No Additional Packages**: Simple flat structure for this educational project

## Resource Organization
- **Layouts**: Single `activity_main.xml` for the main screen
- **Strings**: Minimal strings in `strings.xml` (app name only)
- **Drawables**: Cricket-themed images and standard launcher icons
- **Values**: Standard Android resource files (colors, styles, strings)