# curl : 7.88.1-10+deb12u14.root.io.10

This patch is based on curl version 7.88.1-10+deb12u14.root.io.10, which is available at:
https://sources.debian.org/src/curl/7.88.1-10+deb12u15/

## Affected CVEs:
- CVE-2025-10148
- CVE-2025-0725
- CVE-2025-14819
- CVE-2025-14017
- CVE-2024-2379
- CVE-2025-10966
- CVE-2025-15079
- CVE-2025-14524
- CVE-2026-3783
- CVE-2026-3784
- CVE-2026-1965
- CVE-2026-4873
- CVE-2026-5545
- CVE-2026-5773
- CVE-2026-6253
- CVE-2026-6429
- CVE-2026-7168

## How to Apply:
1. Obtain the source package: `apt source curl`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
