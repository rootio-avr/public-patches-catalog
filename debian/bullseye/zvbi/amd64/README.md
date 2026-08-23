# zvbi : 0.2.35-18.aikido.8

This patch is based on zvbi version 0.2.35-18.aikido.8, which is available at:
https://sources.debian.org/src/zvbi/0.2.35-18/

## Affected CVEs:
- CVE-2025-2174
- CVE-2025-2173
- CVE-2025-2176

## How to Apply:
1. Obtain the source package: `apt source zvbi`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
