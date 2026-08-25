# apparmor : 3.0.8-3.aikido.2

This patch is based on apparmor version 3.0.8-3.aikido.2, which is available at:
https://sources.debian.org/src/apparmor/3.0.8-3/

## Affected CVEs:
- CVE-2016-1585

## How to Apply:
1. Obtain the source package: `apt source apparmor`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
