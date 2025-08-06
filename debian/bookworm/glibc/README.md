# glibc : 2.36-9+deb12u10

This patch is based on glibc version 2.36-9+deb12u10, which is available at:
https://sources.debian.org/src/glibc/2.36-9+deb12u10/

## Affected CVEs:
- CVE-2025-4802
- CVE-2018-20796
- CVE-2019-9192
- CVE-2019-1010022
- CVE-2019-1010023
- CVE-2025-8058

## How to Apply:
1. Download the original Debian source package: `apt source glibc`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -b`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
