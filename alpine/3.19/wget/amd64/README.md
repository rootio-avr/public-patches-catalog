# wget : 1.21.4-r0

This patch is based on wget version 1.21.4-r0, which is available at:
https://ftp.gnu.org/gnu/wget/wget-1.21.4.tar.gz

## Affected CVEs:
- CVE-2024-10524

## How to Apply:
1. Obtain the APKBUILD file and source code: `apk source wget`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `abuild -r`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
