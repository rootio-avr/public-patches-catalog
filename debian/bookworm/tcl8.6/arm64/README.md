# tcl8.6 : 8.6.13+dfsg-2.aikido.3

This patch is based on tcl8.6 version 8.6.13+dfsg-2.aikido.3, which is available at:
https://sources.debian.org/src/tcl8.6/8.6.13+dfsg-2/

## Affected CVEs:
- CVE-2021-35331

## How to Apply:
1. Obtain the source package: `apt source tcl8.6`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
