# libwmf : 0.2.12-5.1.aikido.7

This patch is based on libwmf version 0.2.12-5.1.aikido.7, which is available at:
https://sources.debian.org/src/libwmf/0.2.12-5.1/

## Affected CVEs:
- CVE-2009-3546
- CVE-2007-3477
- CVE-2007-3996
- CVE-2007-3476

## How to Apply:
1. Obtain the source package: `apt source libwmf`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
