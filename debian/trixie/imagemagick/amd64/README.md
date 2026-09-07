# imagemagick : 8:7.1.1.43+dfsg1-1+deb13u11.aikido.38

This patch is based on imagemagick version 8:7.1.1.43+dfsg1-1+deb13u11.aikido.38, which is available at:
https://sources.debian.org/src/imagemagick/8:7.1.1.43+dfsg1-1+deb13u11/

## Affected CVEs:
- CVE-2023-34152
- CVE-2025-55160
- CVE-2026-56362
- CVE-2026-56366
- CVE-2026-56372
- CVE-2026-56373
- CVE-2026-56374
- CVE-2026-56375
- CVE-2026-61465
- CVE-2026-61857
- CVE-2026-61858
- CVE-2026-61859
- CVE-2026-61860
- CVE-2026-61861
- CVE-2026-61863
- CVE-2026-61866
- CVE-2026-61868
- CVE-2026-61870
- CVE-2026-61871
- CVE-2026-62343
- CVE-2026-62363
- CVE-2026-62946
- CVE-2026-64685
- CVE-2026-66011

## How to Apply:
1. Obtain the source package: `apt source imagemagick`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
