# curl : 8.14.1-2+deb13u3.root.io.11

This patch is based on curl version 8.14.1-2+deb13u3.root.io.11, which is available at:
https://sources.debian.org/src/curl/8.14.1-2+deb13u3/

## Affected CVEs:
- CVE-2026-1965
- CVE-2026-3783
- CVE-2026-3805
- CVE-2026-3784
- CVE-2025-14819
- CVE-2025-14524
- CVE-2025-14017
- CVE-2025-15079
- CVE-2025-10966
- CVE-2026-6276
- CVE-2026-5773
- CVE-2026-6253
- CVE-2026-6429
- CVE-2026-4873
- CVE-2026-5545
- CVE-2026-7168
- CVE-2026-8286
- CVE-2026-8932
- CVE-2026-9080
- CVE-2026-9545
- CVE-2026-12064

## How to Apply:
1. Obtain the source package: `apt source curl`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
