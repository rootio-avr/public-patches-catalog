# indent : 2.2.13-r2

This patch is based on indent version 2.2.13-r2, which is available at:
https://ftp.gnu.org/gnu/indent/indent-2.2.13.tar.xz

## Affected CVEs:
- CVE-2023-40305

## How to Apply:
1. Obtain the APKBUILD file and source code: `apk source indent`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `abuild -r`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
