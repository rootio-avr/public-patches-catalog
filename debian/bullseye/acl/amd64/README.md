# acl : 2.2.53-10.root.io.1

This patch is based on acl version 2.2.53-10.root.io.1, which is available at:
https://sources.debian.org/src/acl/2.2.53-10/

## Affected CVEs:
- CVE-2026-54369

## How to Apply:
1. Obtain the source package: `apt source acl`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
