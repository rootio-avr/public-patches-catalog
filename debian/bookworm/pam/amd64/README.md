# pam : 1.5.2-6+deb12u1

This patch is based on pam version 1.5.2-6+deb12u1, which is available at:
https://sources.debian.org/src/pam/1.5.2-6+deb12u1/

## Affected CVEs:
- CVE-2024-22365
- CVE-2024-10041
- CVE-2025-6020

## How to Apply:
1. Download the original Debian source package: `apt source pam`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -b`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
