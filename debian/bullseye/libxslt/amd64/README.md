# libxslt : 1.1.34-4+deb11u3.root.io.8

This patch is based on libxslt version 1.1.34-4+deb11u3.root.io.8, which is available at:
https://sources.debian.org/src/libxslt/1.1.34-4+deb11u3/

## Affected CVEs:
- CVE-2025-10911

## How to Apply:
1. Obtain the source package: `apt source libxslt`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
