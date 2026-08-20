# libssh2 : 1.9.0-2+deb11u1.aikido.5

This patch is based on libssh2 version 1.9.0-2+deb11u1.aikido.5, which is available at:
https://sources.debian.org/src/libssh2/1.9.0-2+deb11u1/

## Affected CVEs:
- CVE-2026-55199
- CVE-2026-55200
- CVE-2026-7598
- CVE-2026-66032
- CVE-2026-66034
- CVE-2026-66033
- CVE-2026-66035
- CVE-2025-15661

## How to Apply:
1. Obtain the source package: `apt source libssh2`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
