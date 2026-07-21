# harfbuzz : 2.7.4-1.root.io.7

This patch is based on harfbuzz version 2.7.4-1.root.io.7, which is available at:
https://sources.debian.org/src/harfbuzz/2.7.4-1/

## Affected CVEs:
- CVE-2023-25193
- CVE-2022-33068
- CVE-2026-22693

## How to Apply:
1. Obtain the source package: `apt source harfbuzz`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
