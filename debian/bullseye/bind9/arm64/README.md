# bind9 : 1:9.16.50-1~deb11u5.root.io.7

This patch is based on bind9 version 1:9.16.50-1~deb11u5.root.io.7, which is available at:
https://sources.debian.org/src/bind9/1:9.16.50-1~deb11u5/

## Affected CVEs:
- CVE-2025-40777
- CVE-2022-2881
- CVE-2026-3039
- CVE-2026-5946

## How to Apply:
1. Obtain the source package: `apt source bind9`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
