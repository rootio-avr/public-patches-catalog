# imagemagick : 8:6.9.11.60+dfsg-1.3+deb11u4.root.io.31

This patch is based on imagemagick version 8:6.9.11.60+dfsg-1.3+deb11u4.root.io.31, which is available at:
https://sources.debian.org/src/imagemagick/8:6.9.11.60+dfsg-1.3+deb11u13/

## Affected CVEs:
- CVE-2023-34152
- CVE-2026-49218
- CVE-2026-53461
- CVE-2026-53460
- CVE-2026-56368
- CVE-2026-56370
- CVE-2026-56361
- CVE-2026-56362
- CVE-2026-33536
- CVE-2026-33535
- CVE-2026-46521
- CVE-2026-25576
- CVE-2026-33899
- CVE-2026-46523
- CVE-2026-53463
- CVE-2026-33905
- CVE-2026-48994
- CVE-2026-46559
- CVE-2026-25983
- CVE-2026-47166
- CVE-2026-46693
- CVE-2026-25988

## How to Apply:
1. Obtain the source package: `apt source imagemagick`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
