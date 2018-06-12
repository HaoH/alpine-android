# Alpine Android ![](https://images.microbadger.com/badges/image/huh09/alpine-android.svg)
some update and fix based on [alvr/alpine-android](https://github.com/alvr/alpine-android)
* OpenJDK updated to 1.8.0_151
* Grale 4.5
* fix bug in Android SDK tools installation

## Content
* OpenJDK 1.8.0_151
* SDK Platform Android 8, API 26, revision 1
* Android SDK Platform-tools, revision 26
* Android SDK Build-tools, revision 26.0.2
* Android Support Repository, revision 47
* Google Play services, revision 43
* Google Repository, revision 57
* Gradle 4.5

---

### Pull from Docker Hub
```sh
docker pull huh09/alpine-android:latest
```

### Pull from Docker Hub
```Dockerfile
FROM huh09/alpine-android:latest
```
