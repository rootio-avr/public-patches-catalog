# hdf5 : 1.10.8+repack1-1

This patch is based on hdf5 version 1.10.8+repack1-1, which is available at:
unknown

## Affected CVEs:
- CVE-2019-8396
- CVE-2019-8398
- CVE-2024-32622

## How to Apply:
1. Download the original Debian source package: `apt source hdf5`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -b`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
