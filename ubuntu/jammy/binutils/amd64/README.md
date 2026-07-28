# binutils : 2.38-4ubuntu2.12.aikido.2

This patch is based on binutils version 2.38-4ubuntu2.12.aikido.2, which is available at:
https://sources.debian.org/src/binutils/2.38-4ubuntu2.12/

## Affected CVEs:
- CVE-2025-1180

## How to Apply:
1. Obtain the source package: `apt source binutils`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `debuild -b -uc -us`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
