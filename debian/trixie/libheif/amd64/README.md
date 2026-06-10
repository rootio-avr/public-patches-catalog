# libheif : 1.19.8-1.root.io.4

This patch is based on libheif version 1.19.8-1.root.io.4, which is available at:
https://sources.debian.org/src/libheif/1.19.8-1/

## Affected CVEs:
- CVE-2025-68431
- CVE-2026-32882
- CVE-2026-32740
- CVE-2026-32741
- CVE-2026-41071

## How to Apply:
1. Obtain the source package: `apt source libheif`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
