# sudo : 1.9.5p2-3+deb11u4.aikido.7

This patch is based on sudo version 1.9.5p2-3+deb11u4.aikido.7, which is available at:
https://sources.debian.org/src/sudo/1.9.5p2-3+deb11u4/

## Affected CVEs:
- CVE-2023-42465

## How to Apply:
1. Obtain the source package: `apt source sudo`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
