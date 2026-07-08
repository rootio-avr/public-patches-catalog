# imagemagick : 8:6.9.11.60+dfsg-1.6+deb12u11.root.io.51

This patch is based on imagemagick version 8:6.9.11.60+dfsg-1.6+deb12u11.root.io.51, which is available at:
https://sources.debian.org/src/imagemagick/8:6.9.11.60+dfsg-1.6+deb12u11/

## Affected CVEs:
- CVE-2023-34152
- CVE-2026-53466
- CVE-2026-53467
- CVE-2026-55577
- CVE-2026-55594
- CVE-2026-55595
- CVE-2026-55597
- CVE-2026-55628
- CVE-2026-56361
- CVE-2026-56365
- CVE-2026-56368
- CVE-2026-56370

## How to Apply:
1. Obtain the source package: `apt source imagemagick`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
