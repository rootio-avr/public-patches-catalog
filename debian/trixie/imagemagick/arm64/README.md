# imagemagick : 8:7.1.1.43+dfsg1-1.root.io.4

This patch is based on imagemagick version 8:7.1.1.43+dfsg1-1.root.io.4, which is available at:
https://sources.debian.org/src/imagemagick/8:7.1.1.43+dfsg1-1/

## Affected CVEs:
- CVE-2025-53015
- CVE-2025-55154
- CVE-2025-55004
- CVE-2025-53019

## How to Apply:
1. Obtain the source package: `apt source imagemagick`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
