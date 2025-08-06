# graphviz : 8.0.5-r2

This patch is based on graphviz version 8.0.5-r2, which is available at:
https://gitlab.com/api/v4/projects/4207231/packages/generic/graphviz-releases/8.0.5/graphviz-8.0.5.tar.xz

## Affected CVEs:
- CVE-2023-46045

## How to Apply:
1. Obtain the APKBUILD file and source code: `apk source graphviz`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `abuild -r`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
