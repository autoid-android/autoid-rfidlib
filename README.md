# autoid-rfidlib
## Usage:
### project.gradle:

```java
  allprojects {
      repositories {
          maven { url "https://raw.githubusercontent.com/autoid-android/autoid-rfidlib/master" }
      }
  }
```

### app.gradle

```java
  implementation 'com.autoid:autoid-rfidlib:1.0.1'
```

## Tree:

```
    .
    ├── scanners
    │   ├── entries
    │   │   ├── T2Scanner.java
    │   │   └── T4Scanner.java
    │   └── Scanner.kt
    └── views
        ├── LocateBottomSheet.kt
        └── PowerController.kt
```

### Current Dependency

```java
    api 'androidx.appcompat:appcompat:1.0.2'
    api 'com.google.android.material:material:1.1.0-alpha07'
    api 'androidx.constraintlayout:constraintlayout:2.0.0-beta1'
    api "androidx.core:core-ktx:1.0.2"
    api "org.jetbrains.kotlin:kotlin-stdlib-jdk7:$kotlin_version"
    api files('libs/t2rfid-release.aar')
    api files('libs/t4-rfid-release.aar')
```
