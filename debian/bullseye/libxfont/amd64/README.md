# libxfont : 1:2.0.4-1.aikido.2

This patch is based on libxfont version 1:2.0.4-1.aikido.2, which is available at:
https://sources.debian.org/src/libxfont/1:2.0.4-1/

## Affected CVEs:
- CVE-2026-56001
- CVE-2026-56002
- CVE-2026-56003

## How to Apply:
1. Obtain the source package: `apt source libxfont`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
