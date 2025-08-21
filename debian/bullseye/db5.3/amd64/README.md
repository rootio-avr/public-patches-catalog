# db5.3 : 5.3.28+dfsg1-0.8.root.io.1

This patch is based on db5.3 version 5.3.28+dfsg1-0.8.root.io.1, which is available at:
https://sources.debian.org/src/db5.3/5.3.28+dfsg1-0.8/

## Affected CVEs:
- CVE-2019-8457

## How to Apply:
1. Obtain the source package: `apt source db5.3`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
