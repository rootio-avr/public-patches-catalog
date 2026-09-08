# unbound : 1.22.0-2+deb13u3.aikido.3

This patch is based on unbound version 1.22.0-2+deb13u3.aikido.3, which is available at:
https://sources.debian.org/src/unbound/1.22.0-2+deb13u3/

## Affected CVEs:
- CVE-2026-32665
- CVE-2026-40691
- CVE-2026-44621
- CVE-2026-44690
- CVE-2026-50045
- CVE-2026-50046
- CVE-2026-50248
- CVE-2026-50251
- CVE-2026-50252
- CVE-2026-55973
- CVE-2026-55990
- CVE-2026-55991
- CVE-2026-56416

## How to Apply:
1. Obtain the source package: `apt source unbound`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
