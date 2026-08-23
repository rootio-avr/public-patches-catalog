# postgresql-13 : 13.23-0+deb11u4.aikido.7

This patch is based on postgresql-13 version 13.23-0+deb11u4.aikido.7, which is available at:
https://sources.debian.org/src/postgresql-13/13.23-0+deb11u4/

## Affected CVEs:
- CVE-2026-14679
- CVE-2026-14677
- CVE-2026-18408
- CVE-2026-14669
- CVE-2026-15742
- CVE-2026-6471
- CVE-2026-16239
- CVE-2026-6464
- CVE-2026-19385
- CVE-2026-15741
- CVE-2026-14662
- CVE-2026-14670
- CVE-2026-14671
- CVE-2026-14664
- CVE-2026-14680
- CVE-2026-14668

## How to Apply:
1. Obtain the source package: `apt source postgresql-13`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
