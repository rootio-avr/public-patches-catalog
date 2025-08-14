# m4 : 1.4.19-3.root.io.2

This patch is based on m4 version 1.4.19-3.root.io.2, which is available at:
https://sources.debian.org/src/m4/1.4.19-3/

## Affected CVEs:
- CVE-2008-1687
- CVE-2008-1688

## How to Apply:
1. Obtain the source package: `apt source m4`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
