# mariadb : 1:10.11.11-0+deb12u1

This patch is based on mariadb version 1:10.11.11-0+deb12u1, which is available at:
unknown

## Affected CVEs:
- CVE-2023-52969
- CVE-2025-30722
- CVE-2025-30693

## How to Apply:
1. Download the original Debian source package: `apt source mariadb`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -b`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
