# imagemagick : 8:6.9.11.60+dfsg-1.6+deb12u8.root.io.46

This patch is based on imagemagick version 8:6.9.11.60+dfsg-1.6+deb12u8.root.io.46, which is available at:
https://sources.debian.org/src/imagemagick/8:6.9.11.60+dfsg-1.6+deb12u8/

## Affected CVEs:
- CVE-2023-34152
- CVE-2026-25637
- CVE-2026-25967
- CVE-2026-25794
- CVE-2026-25971
- CVE-2026-30929
- CVE-2026-28493
- CVE-2026-33901
- CVE-2026-33908
- CVE-2026-34238
- CVE-2026-33902
- CVE-2026-33899
- CVE-2026-33900
- CVE-2026-33905
- CVE-2026-40310
- CVE-2026-40311

## How to Apply:
1. Obtain the source package: `apt source imagemagick`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
