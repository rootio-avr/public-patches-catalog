# wget : 1.21-1+deb11u1.root.io.1

This patch is based on wget version 1.21-1+deb11u1.root.io.1, which is available at:
https://sources.debian.org/src/wget/1.21-1+deb11u1/

## Affected CVEs:
- CVE-2024-10524

## How to Apply:
1. Obtain the source package: `apt source wget`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
