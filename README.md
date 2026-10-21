<p align="center">
  <img src="./logo.png" width="300">
</p>

# Morphe KSU Builder

Builds [KernelSU](https://github.com/tiann/KernelSU) modules with [Morphe](https://github.com/MorpheApp) patches for YouTube, YouTube Music and Reddit.

Flash the ZIPs from the [releases page](https://github.com/LuvHakii/morphe-builder/releases/latest).
Flash the bundled `zygisk-detach-*.zip` once to detach the apps from the Play Store.

## Building locally
```bash
git clone https://github.com/LuvHakii/morphe-builder --depth 1
cd morphe-builder
./build.sh
```
Needs `jq`, `zip`, `openjdk-21`.

## Credits
- [j-hc](https://github.com/j-hc) revanced-magisk-module builder and zygisk-detach.
- [Morphe](https://github.com/MorpheApp) patches.

## License
GPL-3.0, see [LICENSE](LICENSE).
