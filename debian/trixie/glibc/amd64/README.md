# glibc : 2.41-12+deb13u2.root.io.6

This patch is based on glibc version 2.41-12+deb13u2.root.io.6, which is available at:
https://sources.debian.org/src/glibc/2.41-12+deb13u2/

## Affected CVEs:
- CVE-2026-4046
- CVE-2026-4437

## How to Apply:
1. Obtain the source package: `apt source glibc`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
