# libsndfile : 1.2.0-1+deb12u1.aikido.5

This patch is based on libsndfile version 1.2.0-1+deb12u1.aikido.5, which is available at:
https://sources.debian.org/src/libsndfile/1.2.0-1+deb12u1/

## Affected CVEs:
- CVE-2024-50613
- CVE-2022-33064

## How to Apply:
1. Obtain the source package: `apt source libsndfile`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
