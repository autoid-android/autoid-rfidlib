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
  implementation 'com.autoid:autoid-rfidlib:3.1.0'
```

## Tree:

```
.
├── activities
│   └── ErrorActivity.kt
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
    api 'androidx.appcompat:appcompat:1.4.0'
    api 'com.google.android.material:material:1.4.0'
    api 'androidx.constraintlayout:constraintlayout:2.1.2'
    api "androidx.core:core-ktx:1.7.0"
    api "org.jetbrains.kotlin:kotlin-stdlib-jdk7:$kotlin_version"
    compileOnly files('libs/t2rfid-release.aar')
    compileOnly files('libs/t4-rfid-release.aar')
```
