# krb5 : 1.21.3-5.root.io.1

This patch is based on krb5 version 1.21.3-5.root.io.1, which is available at:
https://sources.debian.org/src/krb5/1.21.3-5/

## Affected CVEs:
- CVE-2026-40355
- CVE-2026-40356

## How to Apply:
1. Obtain the source package: `apt source krb5`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
