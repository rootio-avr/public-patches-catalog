# patch : 2.7.6-7build2.aikido.3

This patch is based on patch version 2.7.6-7build2.aikido.3, which is available at:
https://sources.debian.org/src/patch/2.7.6-7build2/

## Affected CVEs:
- CVE-2018-6952

## How to Apply:
1. Obtain the source package: `apt source patch`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `debuild -b -uc -us`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
