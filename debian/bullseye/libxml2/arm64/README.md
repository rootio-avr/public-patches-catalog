# libxml2 : 2.9.10+dfsg-6.7+deb11u4.root.io.6

This patch is based on libxml2 version 2.9.10+dfsg-6.7+deb11u4.root.io.6, which is available at:
https://sources.debian.org/src/libxml2/2.9.10+dfsg-6.7+deb11u9/

## Affected CVEs:
- CVE-2025-12863
- CVE-2026-6653

## How to Apply:
1. Obtain the source package: `apt source libxml2`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
