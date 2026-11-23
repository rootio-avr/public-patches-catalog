# apache2 : 2.4.41-4ubuntu3.23.aikido.1

This patch is based on apache2 version 2.4.41-4ubuntu3.23.aikido.1, which is available at:
https://sources.debian.org/src/apache2/2.4.41-4ubuntu3.23/

## Affected CVEs:
- CVE-2026-119618

## How to Apply:
1. Obtain the source package: `apt source apache2`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `debuild -b -uc -us`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
