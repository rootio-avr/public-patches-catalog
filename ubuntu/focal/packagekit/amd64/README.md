# packagekit : 1.1.13-2ubuntu1.1.aikido.1

This patch is based on packagekit version 1.1.13-2ubuntu1.1.aikido.1, which is available at:
https://sources.debian.org/src/packagekit/1.1.13-2ubuntu1.1/

## Affected CVEs:
- CVE-2026-41651

## How to Apply:
1. Obtain the source package: `apt source packagekit`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `debuild -b -uc -us`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
