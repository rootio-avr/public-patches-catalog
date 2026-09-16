# perl : 5.40.1-6+deb13u1.aikido.11

This patch is based on perl version 5.40.1-6+deb13u1.aikido.11, which is available at:
https://sources.debian.org/src/perl/5.40.1-6+deb13u1/

## Affected CVEs:
- CVE-2026-9538

## How to Apply:
1. Obtain the source package: `apt source perl`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
