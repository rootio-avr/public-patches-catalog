# gnutls28 : 3.8.9-3+deb13u2.root.io.1

This patch is based on gnutls28 version 3.8.9-3+deb13u2.root.io.1, which is available at:
https://sources.debian.org/src/gnutls28/3.8.9-3+deb13u2/

## Affected CVEs:
- CVE-2026-33845

## How to Apply:
1. Obtain the source package: `apt source gnutls28`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
