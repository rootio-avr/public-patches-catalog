# tiff : 4.2.0-1+deb11u7.root.io.15

This patch is based on tiff version 4.2.0-1+deb11u7.root.io.15, which is available at:
https://sources.debian.org/src/tiff/4.2.0-1+deb11u7/

## Affected CVEs:
- CVE-2023-52355
- CVE-2022-40090
- CVE-2023-6277
- CVE-2025-8177
- CVE-2025-8176
- CVE-2025-61144
- CVE-2025-61145
- CVE-2026-4775

## How to Apply:
1. Obtain the source package: `apt source tiff`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
