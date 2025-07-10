# ffmpeg : 7:5.1.6-0+deb12u1

This patch is based on ffmpeg version 7:5.1.6-0+deb12u1, which is available at:
unknown

## Affected CVEs:
- CVE-2025-22921
- CVE-2025-25473
- CVE-2024-36618
- CVE-2025-0518
- CVE-2025-1594
- CVE-2024-31582

## How to Apply:
1. Download the original Debian source package: `apt source ffmpeg`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -b`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
