# shadow : 1:4.13+dfsg1-1.root.io.1

This patch is based on shadow version 1:4.13+dfsg1-1.root.io.1, which is available at:
https://sources.debian.org/src/shadow/1:4.13+dfsg1-1/

## Affected CVEs:
- CVE-2023-4641
- CVE-2023-29383

## How to Apply:
1. Download the original Debian source package: `apt source shadow`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -b`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
