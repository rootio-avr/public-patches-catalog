# gnutls28 : 3.7.9-2+deb12u6.root.io.3

This patch is based on gnutls28 version 3.7.9-2+deb12u6.root.io.3, which is available at:
https://sources.debian.org/src/gnutls28/3.7.9-2+deb12u6/

## Affected CVEs:
- CVE-2026-33846

## How to Apply:
1. Obtain the source package: `apt source gnutls28`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
