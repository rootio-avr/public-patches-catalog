# glibc : 2.35-0ubuntu3.15.aikido.4

This patch is based on glibc version 2.35-0ubuntu3.15.aikido.4, which is available at:
https://sources.debian.org/src/glibc/2.35-0ubuntu3.15/

## Affected CVEs:
- CVE-2026-4437
- CVE-2026-4438

## How to Apply:
1. Obtain the source package: `apt source glibc`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `debuild -b -uc -us`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
