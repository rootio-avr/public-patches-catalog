# mesa : 20.3.5-1.aikido.1

This patch is based on mesa version 20.3.5-1.aikido.1, which is available at:
https://sources.debian.org/src/mesa/20.3.5-1/

## Affected CVEs:
- CVE-2026-40393

## How to Apply:
1. Obtain the source package: `apt source mesa`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
