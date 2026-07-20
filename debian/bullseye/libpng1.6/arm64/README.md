# libpng1.6 : 1.6.37-3+deb11u4.root.io.6

This patch is based on libpng1.6 version 1.6.37-3+deb11u4.root.io.6, which is available at:
https://sources.debian.org/src/libpng1.6/1.6.37-3+deb11u4/

## Affected CVEs:
- CVE-2026-40930

## How to Apply:
1. Obtain the source package: `apt source libpng1.6`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
