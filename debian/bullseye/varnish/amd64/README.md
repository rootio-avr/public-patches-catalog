# varnish : 6.5.1-1+deb11u5.root.io.2

This patch is based on varnish version 6.5.1-1+deb11u5.root.io.2, which is available at:
https://sources.debian.org/src/varnish/6.5.1-1+deb11u5/

## Affected CVEs:
- CVE-2023-44487
- CVE-2026-34475

## How to Apply:
1. Obtain the source package: `apt source varnish`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
