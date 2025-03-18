# postgresql-15 : 15.10-0+deb12u1

This patch is based on postgresql-15 version 15.10-0+deb12u1, which is available at:
https://sources.debian.org/src/postgresql-15/15.10-0+deb12u1/

## Affected CVEs:
- CVE-2025-1094

## How to Apply:
1. Download the original Debian source package: `apt source postgresql-15`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -b`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
