# raptor2 : 2.0.15-4

This patch is based on raptor2 version 2.0.15-4, which is available at:
https://sources.debian.org/src/raptor2/2.0.15-4/

## Affected CVEs:
- CVE-2024-57823

## How to Apply:
1. Download the original Debian source package: `apt source raptor2`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -b`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
