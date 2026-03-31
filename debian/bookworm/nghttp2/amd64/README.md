# nghttp2 : 1.52.0-1+deb12u2.root.io.1

This patch is based on nghttp2 version 1.52.0-1+deb12u2.root.io.1, which is available at:
https://sources.debian.org/src/nghttp2/1.52.0-1+deb12u2/

## Affected CVEs:
- CVE-2026-27135

## How to Apply:
1. Obtain the source package: `apt source nghttp2`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
