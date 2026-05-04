# libgcrypt20 : 1.10.1-3.root.io.4

This patch is based on libgcrypt20 version 1.10.1-3.root.io.4, which is available at:
https://sources.debian.org/src/libgcrypt20/1.10.1-3/

## Affected CVEs:
- CVE-2024-2236
- CVE-2018-6829
- CVE-2026-41989

## How to Apply:
1. Obtain the source package: `apt source libgcrypt20`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
