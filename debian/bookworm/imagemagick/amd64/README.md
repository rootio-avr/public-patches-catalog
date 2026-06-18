# imagemagick : 8:6.9.11.60+dfsg-1.6+deb12u10.root.io.48

This patch is based on imagemagick version 8:6.9.11.60+dfsg-1.6+deb12u10.root.io.48, which is available at:
https://sources.debian.org/src/imagemagick/8:6.9.11.60+dfsg-1.6+deb12u10/

## Affected CVEs:
- CVE-2023-34152
- CVE-2026-46520
- CVE-2026-46522
- CVE-2026-53460
- CVE-2026-49218
- CVE-2026-53461

## How to Apply:
1. Obtain the source package: `apt source imagemagick`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
