# patch : 2.7.6-7.aikido.7

This patch is based on patch version 2.7.6-7.aikido.7, which is available at:
https://sources.debian.org/src/patch/2.7.6-7/

## Affected CVEs:
- CVE-2010-4651
- CVE-2018-6952
- CVE-2018-6951
- CVE-2021-45261

## How to Apply:
1. Obtain the source package: `apt source patch`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
