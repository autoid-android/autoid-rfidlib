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
  implementation 'com.autoid:autoid-rfidlib:1.0.0'
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
