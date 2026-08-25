# libtasn1-6 : 4.19.0-2+deb12u1.aikido.2

This patch is based on libtasn1-6 version 4.19.0-2+deb12u1.aikido.2, which is available at:
https://sources.debian.org/src/libtasn1-6/4.19.0-2+deb12u1/

## Affected CVEs:
- CVE-2025-13151

## How to Apply:
1. Obtain the source package: `apt source libtasn1-6`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
