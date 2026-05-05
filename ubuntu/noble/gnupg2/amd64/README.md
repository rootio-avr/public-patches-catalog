# gnupg2 : 2.4.4-2ubuntu17.root.io.4

This patch is based on gnupg2 version 2.4.4-2ubuntu17.root.io.4, which is available at:
https://sources.debian.org/src/gnupg2/2.4.4-2ubuntu17/

## Affected CVEs:
- CVE-2025-68972

## How to Apply:
1. Obtain the source package: `apt source gnupg2`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `debuild -b -uc -us`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
