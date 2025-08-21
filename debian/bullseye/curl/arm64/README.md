# curl : 7.74.0-1.3+deb11u13.root.io.1

This patch is based on curl version 7.74.0-1.3+deb11u13.root.io.1, which is available at:
https://sources.debian.org/src/curl/7.74.0-1.3+deb11u13/

## Affected CVEs:
- CVE-2022-43551

## How to Apply:
1. Obtain the source package: `apt source curl`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
