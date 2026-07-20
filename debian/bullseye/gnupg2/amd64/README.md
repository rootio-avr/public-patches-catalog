# gnupg2 : 2.2.27-2+deb11u2.root.io.2

This patch is based on gnupg2 version 2.2.27-2+deb11u2.root.io.2, which is available at:
https://sources.debian.org/src/gnupg2/2.2.27-2+deb11u2/

## Affected CVEs:
- CVE-2025-68973
- CVE-2025-30258
- CVE-2025-68972

## How to Apply:
1. Obtain the source package: `apt source gnupg2`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
