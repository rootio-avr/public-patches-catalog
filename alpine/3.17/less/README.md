# less : 608

This patch is based on less version 608, which is available at:
https://www.greenwoodsoftware.com/less/less-608.tar.gz

## Affected CVEs:
- CVE-2022-46663

## How to Apply:
1. Obtain the APKBUILD file and source code: `apk source less`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `abuild -r`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
