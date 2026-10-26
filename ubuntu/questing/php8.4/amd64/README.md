# php8.4 : 8.4.11-1ubuntu1.2.aikido.1

This patch is based on php8.4 version 8.4.11-1ubuntu1.2.aikido.1, which is available at:
https://sources.debian.org/src/php8.4/8.4.11-1ubuntu1.2/

## Affected CVEs:
- CVE-2026-109618
- CVE-2026-109619

## How to Apply:
1. Obtain the source package: `apt source php8.4`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `debuild -b -uc -us`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
