# jq : 1.6-2.1+deb12u2.aikido.8

This patch is based on jq version 1.6-2.1+deb12u2.aikido.8, which is available at:
https://sources.debian.org/src/jq/1.6-2.1+deb12u2/

## Affected CVEs:
- CVE-2024-23337

## How to Apply:
1. Obtain the source package: `apt source jq`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
