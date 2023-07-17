```bash
docker run --rm --volume="$PWD:/app" -w="/app/" adkhambek-android sh -c "./gradlew assembleDebug"
```

## MacOS M1
```bash
docker build --platform linux/amd64 --no-cache --build-arg UID=`id -u` --build-arg GID=`id -g` -t adkhambek-android .
```

## Linux
```bash
docker build --no-cache --build-arg UID=`id -u` --build-arg GID=`id -g` -t adkhambek-android .
```