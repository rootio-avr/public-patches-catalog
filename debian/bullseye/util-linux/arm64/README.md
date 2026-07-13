# util-linux : 2.36.1-8+deb11u2.root.io.2

This patch is based on util-linux version 2.36.1-8+deb11u2.root.io.2, which is available at:
https://sources.debian.org/src/util-linux/2.36.1-8+deb11u2/

## Affected CVEs:
- CVE-2025-14104
- CVE-2026-27456
- CVE-2026-53615

## How to Apply:
1. Obtain the source package: `apt source util-linux`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
