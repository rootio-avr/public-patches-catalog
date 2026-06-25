# sqlite3 : 3.34.1-3+deb11u1.root.io.10

This patch is based on sqlite3 version 3.34.1-3+deb11u1.root.io.10, which is available at:
https://sources.debian.org/src/sqlite3/3.34.1-3+deb11u1/

## Affected CVEs:
- CVE-2025-6965
- CVE-2025-29088
- CVE-2022-35737
- CVE-2026-11822
- CVE-2026-11824

## How to Apply:
1. Obtain the source package: `apt source sqlite3`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
