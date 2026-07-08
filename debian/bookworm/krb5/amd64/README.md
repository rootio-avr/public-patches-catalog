# krb5 : 1.20.1-2+deb12u4.root.io.9

This patch is based on krb5 version 1.20.1-2+deb12u4.root.io.9, which is available at:
https://sources.debian.org/src/krb5/1.20.1-2+deb12u4/

## Affected CVEs:
- CVE-2024-26461
- CVE-2024-26458
- CVE-2018-5709
- CVE-2026-40356
- CVE-2026-40355
- CVE-2026-11850

## How to Apply:
1. Obtain the source package: `apt source krb5`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
