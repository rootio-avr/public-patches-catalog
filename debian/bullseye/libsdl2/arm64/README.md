# libsdl2 : 2.0.14+dfsg2-3+deb11u1.aikido.6

This patch is based on libsdl2 version 2.0.14+dfsg2-3+deb11u1.aikido.6, which is available at:
https://sources.debian.org/src/libsdl2/2.0.14+dfsg2-3+deb11u1/

## Affected CVEs:
- CVE-2022-4743

## How to Apply:
1. Obtain the source package: `apt source libsdl2`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
