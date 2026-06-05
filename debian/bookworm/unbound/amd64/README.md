# unbound : 1.17.1-2+deb12u3.root.io.1

This patch is based on unbound version 1.17.1-2+deb12u3.root.io.1, which is available at:
https://sources.debian.org/src/unbound/1.17.1-2+deb12u3/

## Affected CVEs:
- CVE-2026-33278
- CVE-2026-41292
- CVE-2026-42944
- CVE-2026-42959
- CVE-2026-42960

## How to Apply:
1. Obtain the source package: `apt source unbound`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
