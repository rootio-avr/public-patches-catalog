# glibc : 2.31-13+deb11u14.root.io.14

This patch is based on glibc version 2.31-13+deb11u14.root.io.14, which is available at:
https://sources.debian.org/src/glibc/2.31-13+deb11u14/

## Affected CVEs:
- CVE-2019-1010022
- CVE-2023-4806
- CVE-2023-4813
- CVE-2026-5435
- CVE-2026-5450
- CVE-2026-5928
- CVE-2026-6238

## How to Apply:
1. Obtain the source package: `apt source glibc`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
