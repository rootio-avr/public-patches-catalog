# imagemagick : 8:6.9.11.60+dfsg-1.6+deb12u7.root.io.41

This patch is based on imagemagick version 8:6.9.11.60+dfsg-1.6+deb12u7.root.io.41, which is available at:
https://sources.debian.org/src/imagemagick/8:6.9.11.60+dfsg-1.6+deb12u7/

## Affected CVEs:
- CVE-2023-34152
- CVE-2026-25985
- CVE-2026-25637
- CVE-2026-25967
- CVE-2026-25794
- CVE-2026-28693
- CVE-2026-28691
- CVE-2026-26284
- CVE-2026-28494
- CVE-2026-30883
- CVE-2026-25971
- CVE-2026-30929
- CVE-2026-31853
- CVE-2026-28687
- CVE-2026-28690
- CVE-2026-28688
- CVE-2026-28686
- CVE-2026-32259
- CVE-2026-28493
- CVE-2026-28692
- CVE-2026-28689
- CVE-2026-30937
- CVE-2026-30936
- CVE-2026-26983
- CVE-2026-32636

## How to Apply:
1. Obtain the source package: `apt source imagemagick`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
