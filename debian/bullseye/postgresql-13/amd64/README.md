# postgresql-13 : 13.23-0+deb11u3.root.io.5

This patch is based on postgresql-13 version 13.23-0+deb11u3.root.io.5, which is available at:
https://sources.debian.org/src/postgresql-13/13.23-0+deb11u3/

## Affected CVEs:
- CVE-2026-2004
- CVE-2026-2005
- CVE-2026-2006
- CVE-2026-6479
- CVE-2026-6473
- CVE-2026-6477

## How to Apply:
1. Obtain the source package: `apt source postgresql-13`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
