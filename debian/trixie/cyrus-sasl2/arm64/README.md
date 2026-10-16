# cyrus-sasl2 : 2.1.28+dfsg1-9.aikido.1

This patch is based on cyrus-sasl2 version 2.1.28+dfsg1-9.aikido.1, which is available at:
https://sources.debian.org/src/cyrus-sasl2/2.1.28+dfsg1-9/

## Affected CVEs:
- CVE-2026-107161

## How to Apply:
1. Obtain the source package: `apt source cyrus-sasl2`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
