# pam : 1.5.2-6+deb12u2.root.io.16

This patch is based on pam version 1.5.2-6+deb12u2.root.io.16, which is available at:
https://sources.debian.org/src/pam/1.5.2-6+deb12u2/

## Affected CVEs:
- CVE-2024-10041
- CVE-2026-54411

## How to Apply:
1. Obtain the source package: `apt source pam`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
