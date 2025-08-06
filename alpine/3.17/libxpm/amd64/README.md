# libxpm : 3.5.15-r0

This patch is based on libxpm version 3.5.15-r0, which is available at:
https://www.x.org/releases/individual/lib/libXpm-3.5.15.tar.xz

## Affected CVEs:
- CVE-2023-43789

## How to Apply:
1. Obtain the APKBUILD file and source code: `apk source libxpm`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `abuild -r`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
