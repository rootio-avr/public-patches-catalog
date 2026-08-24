# setuptools : 78.1.1-0.1.aikido.2

This patch is based on setuptools version 78.1.1-0.1.aikido.2, which is available at:
https://sources.debian.org/src/setuptools/78.1.1-0.1/

## Affected CVEs:
- CVE-2026-23949

## How to Apply:
1. Obtain the source package: `apt source setuptools`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
