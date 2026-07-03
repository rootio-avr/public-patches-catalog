# openexr : 2.5.4-2+deb11u1.root.io.14

This patch is based on openexr version 2.5.4-2+deb11u1.root.io.14, which is available at:
https://sources.debian.org/src/openexr/2.5.4-2+deb11u1/

## Affected CVEs:
- CVE-2025-48074
- CVE-2024-31047
- CVE-2025-12839
- CVE-2025-12840
- CVE-2025-12495
- CVE-2026-27622
- CVE-2026-40244
- CVE-2026-40250
- CVE-2026-42217
- CVE-2026-41142
- CVE-2026-42216
- CVE-2026-34588
- CVE-2026-34379
- CVE-2026-34545

## How to Apply:
1. Obtain the source package: `apt source openexr`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
