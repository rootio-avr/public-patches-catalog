# imagemagick : 8:6.9.11.60+dfsg-1.6+deb12u3

This patch is based on imagemagick version 8:6.9.11.60+dfsg-1.6+deb12u3, which is available at:
unknown

## Affected CVEs:
- CVE-2025-53101

## How to Apply:
1. Download the original Debian source package: `apt source imagemagick`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -b`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
