# curl : 8.5.0-2ubuntu10.11.aikido.1

This patch is based on curl version 8.5.0-2ubuntu10.11.aikido.1, which is available at:
https://sources.debian.org/src/curl/8.5.0-2ubuntu10.11/

## Affected CVEs:
- CVE-2026-11856

## How to Apply:
1. Obtain the source package: `apt source curl`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `debuild -b -uc -us`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
