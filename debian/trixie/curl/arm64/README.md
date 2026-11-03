# curl : 8.14.1-2+deb13u7.aikido.25

This patch is based on curl version 8.14.1-2+deb13u7.aikido.25, which is available at:
https://sources.debian.org/src/curl/8.14.1-2+deb13u7/

## Affected CVEs:
- CVE-2025-10966
- CVE-2025-14017
- CVE-2025-15079
- CVE-2026-12064
- CVE-2026-8932
- CVE-2026-9079
- CVE-2026-9080
- CVE-2026-9545
- CVE-2026-9547
- CVE-2026-11856
- CVE-2026-8926
- CVE-2026-10536
- CVE-2026-8458
- CVE-2026-18924
- CVE-2026-13608
- CVE-2026-80230
- CVE-2026-80255
- CVE-2026-80229
- CVE-2026-82209
- CVE-2026-19931
- CVE-2026-107928
- CVE-2026-107929
- CVE-2026-86409
- CVE-2026-86410
- CVE-2026-86414
- CVE-2026-87862
- CVE-2026-87863
- CVE-2026-87864
- CVE-2026-87865
- CVE-2026-92386
- CVE-2026-92387
- CVE-2026-92388
- CVE-2026-92389
- CVE-2026-92390
- CVE-2026-92391
- CVE-2026-94266

## How to Apply:
1. Obtain the source package: `apt source curl`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
