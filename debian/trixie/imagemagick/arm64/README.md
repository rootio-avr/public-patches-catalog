# imagemagick : 8:7.1.1.43+dfsg1-1+deb13u8.root.io.33

This patch is based on imagemagick version 8:7.1.1.43+dfsg1-1+deb13u8.root.io.33, which is available at:
https://sources.debian.org/src/imagemagick/8:7.1.1.43+dfsg1-1+deb13u8/

## Affected CVEs:
- CVE-2025-55160
- CVE-2023-34152
- CVE-2026-46520
- CVE-2026-46522
- CVE-2026-47166
- CVE-2026-47165
- CVE-2026-46692
- CVE-2026-46693
- CVE-2026-45624
- CVE-2026-42050
- CVE-2026-46521
- CVE-2026-46557
- CVE-2026-46559
- CVE-2026-46523
- CVE-2026-45664
- CVE-2026-42326
- CVE-2026-45031
- CVE-2026-45358
- CVE-2026-45359
- CVE-2026-56370
- CVE-2026-56368
- CVE-2026-56361

## How to Apply:
1. Obtain the source package: `apt source imagemagick`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
