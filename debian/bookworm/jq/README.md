# jq : 1.6-2.1

This patch is based on jq version 1.6-2.1, which is available at:
unknown

## Affected CVEs:
- CVE-2024-53427
- CVE-2025-48060

## How to Apply:
1. Download the original Debian source package: `apt source jq`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -b`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
