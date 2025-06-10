# ghostscript : 10.0.0~dfsg-11+deb12u7

This patch is based on ghostscript version 10.0.0~dfsg-11+deb12u7, which is available at:
unknown

## Affected CVEs:
- CVE-2025-48708
- CVE-2024-29511
- CVE-2023-38560

## How to Apply:
1. Download the original Debian source package: `apt source ghostscript`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -b`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
