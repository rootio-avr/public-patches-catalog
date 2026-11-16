# krb5 : 1.21.3-5+deb13u1.aikido.5

This patch is based on krb5 version 1.21.3-5+deb13u1.aikido.5, which is available at:
https://sources.debian.org/src/krb5/1.21.3-5+deb13u1/

## Affected CVEs:
- CVE-2026-11850
- CVE-2026-107778
- CVE-2026-112323
- CVE-2026-119079
- CVE-2026-112321
- CVE-2026-112320
- CVE-2026-112314
- CVE-2026-112322

## How to Apply:
1. Obtain the source package: `apt source krb5`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
