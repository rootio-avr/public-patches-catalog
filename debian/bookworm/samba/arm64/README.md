# samba : 2:4.17.12+dfsg-0+deb12u2.aikido.2

This patch is based on samba version 2:4.17.12+dfsg-0+deb12u2.aikido.2, which is available at:
https://sources.debian.org/src/samba/2:4.17.12+dfsg-0+deb12u2/

## Affected CVEs:
- CVE-2025-10230

## How to Apply:
1. Obtain the source package: `apt source samba`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
