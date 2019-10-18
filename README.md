# Android Helpful documentation

## Installing from command line interface

### Windows

Pre-requisites:

1. Android SDK with build tools

---

**Installing**
Open command prompt in administrator mode

go till platfrom-tools/ folder, then

```sh
adb install "path_to_apk"
```

to update an apk

```sh
adb install -r "path_to_apk"
```

to uninstall apk

```sh
adb uninstall "package_name_of_the_apk"
```