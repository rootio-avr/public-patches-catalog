# cairo : 1.16.0-7.aikido.5

This patch is based on cairo version 1.16.0-7.aikido.5, which is available at:
https://sources.debian.org/src/cairo/1.16.0-7/

## Affected CVEs:
- CVE-2025-50422
- CVE-2019-6461
- CVE-2019-6462

## How to Apply:
1. Obtain the source package: `apt source cairo`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
