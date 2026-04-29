# glibc : 2.36-9+deb12u13.root.io.16

This patch is based on glibc version 2.36-9+deb12u13.root.io.16, which is available at:
https://sources.debian.org/src/glibc/2.36-9+deb12u13/

## Affected CVEs:
- CVE-2018-20796
- CVE-2019-9192
- CVE-2019-1010022
- CVE-2019-1010023
- CVE-2026-0915
- CVE-2026-0861
- CVE-2025-15281
- CVE-2026-4437
- CVE-2026-4438
- CVE-2026-5928

## How to Apply:
1. Obtain the source package: `apt source glibc`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
