# libheif : 1.11.0-1+deb11u2.root.io.4

This patch is based on libheif version 1.11.0-1+deb11u2.root.io.4, which is available at:
https://sources.debian.org/src/libheif/1.11.0-1+deb11u2/

## Affected CVEs:
- CVE-2025-68431
- CVE-2026-32740
- CVE-2026-32882
- CVE-2026-32741
- CVE-2026-41071
- CVE-2026-41069
- CVE-2026-32814
- CVE-2026-32739
- CVE-2026-47178
- CVE-2026-49271

## How to Apply:
1. Obtain the source package: `apt source libheif`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
