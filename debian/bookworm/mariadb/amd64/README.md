# mariadb : 1:10.11.14-0+deb12u2.root.io.5

This patch is based on mariadb version 1:10.11.14-0+deb12u2.root.io.5, which is available at:
https://sources.debian.org/src/mariadb/1:10.11.14-0+deb12u2/

## Affected CVEs:
- CVE-2025-13699
- CVE-2026-21968
- CVE-2026-48163
- CVE-2026-48165
- CVE-2026-44168

## How to Apply:
1. Obtain the source package: `apt source mariadb`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
