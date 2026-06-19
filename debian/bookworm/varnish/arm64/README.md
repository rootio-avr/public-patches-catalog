# varnish : 7.1.1-2+deb12u1.root.io.7

This patch is based on varnish version 7.1.1-2+deb12u1.root.io.7, which is available at:
https://sources.debian.org/src/varnish/7.1.1-2+deb12u1/

## Affected CVEs:
- CVE-2024-30156
- CVE-2023-44487
- CVE-2026-34475

## How to Apply:
1. Obtain the source package: `apt source varnish`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
