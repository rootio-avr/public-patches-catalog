# unixodbc : 2.3.11-2+deb12u1.aikido.2

This patch is based on unixodbc version 2.3.11-2+deb12u1.aikido.2, which is available at:
https://sources.debian.org/src/unixodbc/2.3.11-2+deb12u1/

## Affected CVEs:
- CVE-2024-1013

## How to Apply:
1. Obtain the source package: `apt source unixodbc`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
