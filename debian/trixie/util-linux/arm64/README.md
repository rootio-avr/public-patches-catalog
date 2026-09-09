# util-linux : 2.41.5-0+deb13u1.aikido.7

This patch is based on util-linux version 2.41.5-0+deb13u1.aikido.7, which is available at:
https://sources.debian.org/src/util-linux/2.41.5-0+deb13u1/

## Affected CVEs:
- CVE-2026-3184
- CVE-2026-53615
- CVE-2026-76642
- CVE-2026-78408
- CVE-2026-78409
- CVE-2026-78410

## How to Apply:
1. Obtain the source package: `apt source util-linux`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
