# nginx : 1.20.2-r20071

This patch is based on nginx version 1.20.2-r20071, which is available at:
unknown

## Affected CVEs:
- CVE-2026-42945
- CVE-2026-27651
- CVE-2026-60005
- CVE-2026-1642
- CVE-2026-42533
- CVE-2026-32647
- CVE-2026-27654
- CVE-2026-42946
- CVE-2026-56434

## How to Apply:
1. Obtain the APKBUILD file and source code: `apk source nginx`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `abuild -r`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
