# mariadb : 1:10.11.18-0+deb12u1.aikido.7

This patch is based on mariadb version 1:10.11.18-0+deb12u1.aikido.7, which is available at:
https://sources.debian.org/src/mariadb/1:10.11.18-0+deb12u1/

## Affected CVEs:
- CVE-2026-44169

## How to Apply:
1. Obtain the source package: `apt source mariadb`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
