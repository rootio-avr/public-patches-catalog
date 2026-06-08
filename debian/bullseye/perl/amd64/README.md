# perl : 5.32.1-4+deb11u5.root.io.2

This patch is based on perl version 5.32.1-4+deb11u5.root.io.2, which is available at:
https://sources.debian.org/src/perl/5.32.1-4+deb11u5/

## Affected CVEs:
- CVE-2025-40909
- CVE-2026-8376
- CVE-2026-42496
- CVE-2026-9538
- CVE-2026-48962
- CVE-2026-42497

## How to Apply:
1. Obtain the source package: `apt source perl`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
