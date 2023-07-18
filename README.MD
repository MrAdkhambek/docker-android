# Android docker image

| Library               | Version           |
| :---                  |       :----:      |
| ANDROID VERSION       | 33                |
| BUILD TOOLS           | [33.0.0, 30.0.3]  |
| ANDROID NDK VERSION   | 25.2.9519653      |

# Sample command

```bash
docker run --rm --volume="$PWD:/app" -w="/app/" mradkhambek/android-33 sh -c "./gradlew assembleDebug"
```

# OR
```bash
docker run --rm --volume="$PWD:/app" -w="/app/" mradkhambek/android-33 sh -c "gradle assembleDebug"
```