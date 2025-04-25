# nghttp2 : 1.58.0-r0

This patch is based on nghttp2 version 1.58.0-r0, which is available at:
https://github.com/nghttp2/nghttp2/releases/download/v1.58.0/nghttp2-1.58.0.tar.xz

## Affected CVEs:
- CVE-2024-28182

## How to Apply:
1. Obtain the APKBUILD file and source code: `apk source nghttp2`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `abuild -r`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
