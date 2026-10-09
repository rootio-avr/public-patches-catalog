# xorg-server : 2:1.20.11-1+deb11u18.aikido.13

This patch is based on xorg-server version 2:1.20.11-1+deb11u18.aikido.13, which is available at:
https://sources.debian.org/src/xorg-server/2:1.20.11-1+deb11u18/

## Affected CVEs:
- CVE-2023-5574
- CVE-2026-55999
- CVE-2026-56000

## How to Apply:
1. Obtain the source package: `apt source xorg-server`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
