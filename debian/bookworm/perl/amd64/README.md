# perl : 5.36.0-7+deb12u4.aikido.20

This patch is based on perl version 5.36.0-7+deb12u4.aikido.20, which is available at:
https://sources.debian.org/src/perl/5.36.0-7+deb12u4/

## Affected CVEs:
- CVE-2011-4116
- CVE-2023-31486
- CVE-2026-9538
- CVE-2026-82560

## How to Apply:
1. Obtain the source package: `apt source perl`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
