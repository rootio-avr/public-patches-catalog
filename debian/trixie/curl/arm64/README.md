# curl : 8.14.1-2+deb13u2.root.io.8

This patch is based on curl version 8.14.1-2+deb13u2.root.io.8, which is available at:
https://sources.debian.org/src/curl/8.14.1-2+deb13u2/

## Affected CVEs:
- CVE-2025-13034
- CVE-2026-1965
- CVE-2026-3783
- CVE-2026-3805
- CVE-2026-3784
- CVE-2025-14819
- CVE-2025-14524
- CVE-2025-14017
- CVE-2025-15079
- CVE-2025-10966

## How to Apply:
1. Obtain the source package: `apt source curl`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
