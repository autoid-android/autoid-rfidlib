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
  implementation 'com.autoid:autoid-rfidlib:1.0.7'
```

## Tree:

```
    .
    ├── scanners
    │   ├── entries
    │   │   ├── T2Scanner.java
    │   │   └── T4Scanner.java
    │   └── Scanner.kt
    ├── utils
    │   └── SGTIN96Util.java
    └── views
        ├── LocateBottomSheet.kt
        └── PowerController.kt
```

### Current Dependency

```java
    api 'androidx.appcompat:appcompat:1.1.0'
    api 'com.google.android.material:material:1.2.0-alpha03'
    api 'androidx.constraintlayout:constraintlayout:2.0.0-beta4'
    api "androidx.core:core-ktx:1.1.0"
    compileOnly files('libs/t2rfid-release.aar')
    compileOnly files('libs/t4-rfid-release.aar')
```
