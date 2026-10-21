<p align="center">
  <img src="./logo.png" width="300">
</p>

# Morphe KSU Builder

Builds [KernelSU](https://github.com/tiann/KernelSU) modules with [Morphe](https://github.com/MorpheApp) patches for YouTube, YouTube Music and Reddit.

Flash the ZIPs from the [releases page](https://github.com/sixstrings/morphe-builder/releases/latest).
Flash the bundled `zygisk-detach-*.zip` once to detach the apps from the Play Store.

## Building locally
```bash
git clone https://github.com/sixstrings/morphe-builder --depth 1
cd morphe-builder
./build.sh
```
Needs `jq`, `zip`, `openjdk-21`.

## Credits
- [j-hc](https://github.com/j-hc) builder and zygisk-detach.
- [Morphe](https://github.com/MorpheApp) patches.
- [peternmuller](https://github.com/peternmuller/revanced-morphe-builder) fork.

## License
    Copyright (C) 2024-2026

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program. If not, see <https://www.gnu.org/licenses/>.

    
