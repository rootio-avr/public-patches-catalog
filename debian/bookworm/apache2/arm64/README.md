# apache2 : 2.4.62-1~deb12u2.root.io.7

This patch is based on apache2 version 2.4.62-1~deb12u2.root.io.7, which is available at:
https://sources.debian.org/src/apache2/2.4.62-1~deb12u2/

## Affected CVEs:
- CVE-2024-43204
- CVE-2024-42516
- CVE-2024-47252
- CVE-2007-0086
- CVE-2025-23048
- CVE-2025-49630
- CVE-2025-53020
- CVE-2025-49812

## How to Apply:
1. Obtain the source package: `apt source apache2`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
