# libevent : 2.1.12-stable-8.aikido.3

This patch is based on libevent version 2.1.12-stable-8.aikido.3, which is available at:
https://sources.debian.org/src/libevent/2.1.12-stable-8/

## Affected CVEs:
- CVE-2026-63382
- CVE-2026-63385
- CVE-2026-63383
- CVE-2026-63384
- CVE-2026-63388

## How to Apply:
1. Obtain the source package: `apt source libevent`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
