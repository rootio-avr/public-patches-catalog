# sqlite : 3.45.3-r30071

This patch is based on sqlite version 3.45.3-r30071, which is available at:
unknown

## Affected CVEs:
- CVE-2025-70873
- CVE-2026-11824
- CVE-2026-11822
- CVE-2025-3277

## How to Apply:
1. Obtain the APKBUILD file and source code: `apk source sqlite`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `abuild -r`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
