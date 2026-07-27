# curl : 7.88.1-10+deb12u15.aikido.13

This patch is based on curl version 7.88.1-10+deb12u15.aikido.13, which is available at:
https://sources.debian.org/src/curl/7.88.1-10+deb12u15/

## Affected CVEs:
- CVE-2025-0725
- CVE-2025-14017
- CVE-2024-2379
- CVE-2025-10966
- CVE-2025-15079
- CVE-2026-1965
- CVE-2026-4873
- CVE-2026-5545
- CVE-2026-6253
- CVE-2026-6276
- CVE-2026-6429
- CVE-2026-8286
- CVE-2026-8932
- CVE-2026-9547
- CVE-2026-12064
- CVE-2026-8458
- CVE-2026-10536
- CVE-2026-8924
- CVE-2026-11856
- CVE-2026-8927

## How to Apply:
1. Obtain the source package: `apt source curl`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
