# openldap : 2.5.13+dfsg-5

This patch is based on openldap version 2.5.13+dfsg-5, which is available at:
https://sources.debian.org/src/openldap/2.5.13+dfsg-5/

## Affected CVEs:
- CVE-2023-2953
- CVE-2017-17740

## How to Apply:
1. Download the original Debian source package: `apt source openldap`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -b`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
