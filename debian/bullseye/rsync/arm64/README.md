# rsync : 3.2.3-4+deb11u4.aikido.1

This patch is based on rsync version 3.2.3-4+deb11u4.aikido.1, which is available at:
https://sources.debian.org/src/rsync/3.2.3-4+deb11u4/

## Affected CVEs:
- CVE-2026-53791
- CVE-2026-53803
- CVE-2026-70453
- CVE-2026-70463
- CVE-2026-53784
- CVE-2026-70458
- CVE-2026-53802

## How to Apply:
1. Obtain the source package: `apt source rsync`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
