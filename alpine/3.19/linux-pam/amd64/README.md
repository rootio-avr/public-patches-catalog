# linux-pam : 1.5.3-r7

This patch is based on linux-pam version 1.5.3-r7, which is available at:
https://github.com/linux-pam/linux-pam/releases/download/v1.5.3/Linux-PAM-1.5.3.tar.xz

## Affected CVEs:
- CVE-2024-22365

## How to Apply:
1. Obtain the APKBUILD file and source code: `apk source linux-pam`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `abuild -r`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
