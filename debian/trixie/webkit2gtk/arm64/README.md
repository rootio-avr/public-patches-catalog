# webkit2gtk : 2.52.6-1~deb13u1.aikido.1

This patch is based on webkit2gtk version 2.52.6-1~deb13u1.aikido.1, which is available at:
https://sources.debian.org/src/webkit2gtk/2.52.6-1~deb13u1/

## Affected CVEs:
- CVE-2026-78376
- CVE-2026-83596

## How to Apply:
1. Obtain the source package: `apt source webkit2gtk`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
