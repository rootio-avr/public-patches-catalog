# apache2 : 2.4.67-1~deb12u3.root.io.11

This patch is based on apache2 version 2.4.67-1~deb12u3.root.io.11, which is available at:
https://sources.debian.org/src/apache2/2.4.67-1~deb12u3/

## Affected CVEs:
- CVE-2007-0086
- CVE-2026-29167
- CVE-2026-34355
- CVE-2026-34356
- CVE-2026-42535
- CVE-2026-42536
- CVE-2026-44185
- CVE-2026-44186
- CVE-2026-44631
- CVE-2026-48913

## How to Apply:
1. Obtain the source package: `apt source apache2`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
