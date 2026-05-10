# pam : 1.4.0-11ubuntu2.6.root.io.3

This patch is based on pam version 1.4.0-11ubuntu2.6.root.io.3, which is available at:
https://sources.debian.org/src/pam/1.4.0-11ubuntu2.6/

## Affected CVEs:
- CVE-2025-8941

## How to Apply:
1. Obtain the source package: `apt source pam`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `debuild -b -uc -us`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
