# sudo : 1.8.31-1ubuntu1.5.aikido.1

This patch is based on sudo version 1.8.31-1ubuntu1.5.aikido.1, which is available at:
https://sources.debian.org/src/sudo/1.8.31-1ubuntu1.5/

## Affected CVEs:
- CVE-2025-32462

## How to Apply:
1. Obtain the source package: `apt source sudo`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `debuild -b -uc -us`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
