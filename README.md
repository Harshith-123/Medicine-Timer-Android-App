# Medicine Time Android App

Medicine Time is an Android mobile application designed to help users manage their medicine schedule and receive timely reminders for taking medicines. The app provides a simple interface to add medicine details, set dosage information, schedule reminder times, and manage medicine records efficiently.

## Project Overview

Many people forget to take their medicines on time, especially when they have multiple medicines with different schedules. This app helps solve that problem by allowing users to create medicine reminders and keep track of their medication routine in one place.

The main goal of this project is to provide a user-friendly Android application that supports basic medicine reminder management and improves medication discipline.

## Features

- Add medicine details
- Set medicine reminder time
- View saved medicine records
- Update or manage medicine information
- Delete medicine records when no longer needed
- Simple and easy-to-use Android interface
- Local storage/database support for saving medicine details
- Reminder-based functionality for medicine timing

## Technologies Used

- Java
- Android Studio
- Gradle
- Android SDK
- XML for UI design
- SQLite/local database storage

## Project Structure

```text
Medicine-Time-Android-App/
│
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   ├── res/
│   │   │   └── AndroidManifest.xml
│   │
│   └── build.gradle
│
├── gradle/
├── build.gradle
├── settings.gradle
├── gradle.properties
├── gradlew
├── gradlew.bat
├── LICENSE
└── README.md
````

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
```

### 2. Open the Project in Android Studio

Open Android Studio and select:

```text
File > Open
```

Then choose the project folder.

### 3. Sync Gradle

After opening the project, allow Android Studio to sync Gradle files.

If it does not sync automatically, click:

```text
File > Sync Project with Gradle Files
```

### 4. Run the App

Connect an Android device or start an emulator, then click the **Run** button in Android Studio.

## Requirements

* Android Studio
* Java Development Kit
* Android SDK
* Android Emulator or physical Android device

## How to Build APK

To generate an APK:

```text
Build > Build Bundle(s) / APK(s) > Build APK(s)
```

After the build is completed, Android Studio will show the APK location.

## Git Setup Notes

The following files and folders are ignored using `.gitignore` because they are generated locally or contain machine-specific settings:

```text
.gradle/
build/
app/build/
local.properties
.idea/
*.iml
*.apk
*.aab
```

## Future Enhancements

* Add user login and profile management
* Add notification customization
* Add medicine history tracking
* Add missed-dose tracking
* Add support for multiple users
* Improve UI/UX design
* Add cloud backup support
* Add medicine stock/refill reminders

## License

This project is created for academic and learning purposes.

## Author

Harshith Basavaraju
