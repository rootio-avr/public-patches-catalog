# wget : 1.25.0-r10071

This patch is based on wget version 1.25.0-r10071, which is available at:
unknown

## Affected CVEs:
- CVE-2026-58469
- CVE-2026-58471
- CVE-2026-58472

## How to Apply:
1. Obtain the APKBUILD file and source code: `apk source wget`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `abuild -r`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
