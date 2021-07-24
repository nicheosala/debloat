# Debloating Android
[debloated_packages.txt](./debloated_packages.txt) contains the list of packages I removed from a clean LineageOS 18.1 installation.

## How to
In order to uninstall a package `<package_name>`, link the smartphone to ADB and then type:
```bash
adb shell pm uninstall --user 0 <package_name>
```
If you want to reinstall a package `<package_name>`, type:
```bash
adb shell cmd package install-existing <package_name>
```

## Useful resources
- [Universal Android Debloater](https://gitlab.com/W1nst0n/universal-android-debloater)