# tar : 1.35+dfsg-3.1.root.io.2

This patch is based on tar version 1.35+dfsg-3.1.root.io.2, which is available at:
https://sources.debian.org/src/tar/1.35+dfsg-3.1/

## Affected CVEs:
- CVE-2005-2541
- CVE-2026-5704

## How to Apply:
1. Obtain the source package: `apt source tar`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
