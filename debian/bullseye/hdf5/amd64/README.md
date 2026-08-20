# hdf5 : 1.10.6+repack-4+deb11u1.aikido.12

This patch is based on hdf5 version 1.10.6+repack-4+deb11u1.aikido.12, which is available at:
https://sources.debian.org/src/hdf5/1.10.6+repack-4+deb11u1/

## Affected CVEs:
- CVE-2024-29157
- CVE-2022-25942
- CVE-2024-29164
- CVE-2024-32621
- CVE-2024-32622
- CVE-2024-29161
- CVE-2025-2153

## How to Apply:
1. Obtain the source package: `apt source hdf5`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
