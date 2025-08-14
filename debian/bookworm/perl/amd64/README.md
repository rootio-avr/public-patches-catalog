# perl : 5.36.0-7+deb12u2.root.io.3

This patch is based on perl version 5.36.0-7+deb12u2.root.io.3, which is available at:
https://sources.debian.org/src/perl/5.36.0-7+deb12u2/

## Affected CVEs:
- CVE-2023-31484
- CVE-2025-40909
- CVE-2011-4116
- CVE-2023-31486

## How to Apply:
1. Obtain the source package: `apt source perl`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
