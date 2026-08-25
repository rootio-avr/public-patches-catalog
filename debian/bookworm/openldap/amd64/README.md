# openldap : 2.5.13+dfsg-5.aikido.7

This patch is based on openldap version 2.5.13+dfsg-5.aikido.7, which is available at:
https://sources.debian.org/src/openldap/2.5.13+dfsg-5/

## Affected CVEs:
- CVE-2023-2953
- CVE-2017-17740
- CVE-2015-3276
- CVE-2020-15719
- CVE-2026-22185

## How to Apply:
1. Obtain the source package: `apt source openldap`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
