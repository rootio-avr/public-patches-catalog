# nodejs : 18.19.0+dfsg-6~deb12u2

This patch is based on nodejs version 18.19.0+dfsg-6~deb12u2, which is available at:
unknown

## Affected CVEs:
- CVE-2024-21892
- CVE-2023-46809
- CVE-2024-22019
- CVE-2024-22020
- CVE-2024-27983
- CVE-2025-23166
- CVE-2025-23083
- CVE-2024-22025
- CVE-2025-23085
- CVE-2024-27982
- CVE-2025-23165

## How to Apply:
1. Download the original Debian source package: `apt source nodejs`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -b`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
