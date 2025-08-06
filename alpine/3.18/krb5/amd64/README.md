# krb5 : 1.20.2-r1

This patch is based on krb5 version 1.20.2-r1, which is available at:
unknown

## Affected CVEs:
- CVE-2000-0546
- CVE-2000-0547
- CVE-2000-0548

## How to Apply:
1. Obtain the APKBUILD file and source code: `apk source krb5`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `abuild -r`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
