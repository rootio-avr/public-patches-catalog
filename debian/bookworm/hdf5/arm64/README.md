# hdf5 : 1.10.8+repack1-1.root.io.6

This patch is based on hdf5 version 1.10.8+repack1-1.root.io.6, which is available at:
https://sources.debian.org/src/hdf5/1.10.8+repack1-1/

## Affected CVEs:
- CVE-2019-8396
- CVE-2019-8398
- CVE-2024-32622
- CVE-2024-32606
- CVE-2021-46242
- CVE-2018-14031

## How to Apply:
1. Obtain the source package: `apt source hdf5`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
