# apache2 : 2.4.62-1~deb12u2

This patch is based on apache2 version 2.4.62-1~deb12u2, which is available at:
unknown

## Affected CVEs:
- CVE-2024-42516

## How to Apply:
1. Download the original Debian source package: `apt source apache2`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -b`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
