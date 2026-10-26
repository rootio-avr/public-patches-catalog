# php7.4 : 7.4.3-4ubuntu2.29.aikido.1

This patch is based on php7.4 version 7.4.3-4ubuntu2.29.aikido.1, which is available at:
https://sources.debian.org/src/php7.4/7.4.3-4ubuntu2.29/

## Affected CVEs:
- CVE-2026-109618
- CVE-2026-109619

## How to Apply:
1. Obtain the source package: `apt source php7.4`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `debuild -b -uc -us`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
