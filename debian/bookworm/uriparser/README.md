# uriparser : 0.9.7+dfsg-2.root.io.1

This patch is based on uriparser version 0.9.7+dfsg-2.root.io.1, which is available at:
https://sources.debian.org/src/uriparser/0.9.7+dfsg-2/

## Affected CVEs:
- CVE-2024-34403
- CVE-2024-34402

## How to Apply:
1. Download the original Debian source package: `apt source uriparser`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -b`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
