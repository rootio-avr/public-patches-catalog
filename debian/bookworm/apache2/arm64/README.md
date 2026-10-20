# apache2 : 2.4.68-1~deb12u1.aikido.15

This patch is based on apache2 version 2.4.68-1~deb12u1.aikido.15, which is available at:
https://sources.debian.org/src/apache2/2.4.68-1~deb12u1/

## Affected CVEs:
- CVE-2007-0086
- CVE-2026-46729
- CVE-2026-47360
- CVE-2026-48005
- CVE-2026-56153
- CVE-2026-56154
- CVE-2026-56449
- CVE-2026-57941
- CVE-2026-59797
- CVE-2026-63045
- CVE-2026-63292
- CVE-2026-63686
- CVE-2026-63718
- CVE-2026-73636
- CVE-2026-73637
- CVE-2026-93546

## How to Apply:
1. Obtain the source package: `apt source apache2`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
