# perl : 5.40.1-6.root.io.4

This patch is based on perl version 5.40.1-6.root.io.4, which is available at:
https://sources.debian.org/src/perl/5.40.1-6/

## Affected CVEs:
- CVE-2026-42496
- CVE-2026-9538
- CVE-2026-8376
- CVE-2026-42497
- CVE-2026-48962
- CVE-2026-48959
- CVE-2026-7010
- CVE-2025-15649

## How to Apply:
1. Obtain the source package: `apt source perl`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
