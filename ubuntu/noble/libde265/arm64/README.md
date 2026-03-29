# libde265 : 1.0.15-1build3.root.io.2

This patch is based on libde265 version 1.0.15-1build3.root.io.2, which is available at:
https://sources.debian.org/src/libde265/1.0.15-1build3/

## Affected CVEs:
- CVE-2024-38950

## How to Apply:
1. Obtain the source package: `apt source libde265`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `debuild -b -uc -us`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
